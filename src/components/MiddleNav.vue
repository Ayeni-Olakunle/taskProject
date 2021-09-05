<template>
    <div id="people">
        <h4>People</h4><br>
            <div class="cate">
                <span class="all">All</span>
                <span class="organ">Oraganization</span>
            </div>
            <div class="cateLine"></div>
            <div class="holdFilter">
                <b-input-group prepend="Filters:" class="mb-2 mr-sm-2 mb-sm-0" style="width: fit-content;">
                <select name="" id="filters">
                    <option>Select Options</option>
                    <option>Most Recent</option>
                </select>
                </b-input-group>
                <div class="searchDiv">
                    <div class="holdSearch">
                        <div class="h5 mb-0">
                            <b-icon icon="search" variant="secondary"></b-icon>
                        </div>
                        <input type="text" placeholder="Search here" class="searchinner">
                    </div>
                </div>
            </div>
            <div>
                <b-container fluid class="bv-example-row" style="padding: 0;">
                    <b-row>
                        <b-col sm="4">
                            <div class="holdW">
                                <Workers name="John Ohue" position="CREATIVE DIRECTOR" email="john23@yopmail.com" pic="man2.jpg" />
                            </div>
                        </b-col>
                        <b-col sm="4">
                            <div class="holdW">
                                <Workers name="Sarah Bright" position="CREATIVE DIRECTOR" email="sarah@yopmail.com" pic="man1.jpg" />
                            </div>
                        </b-col>
                        <b-col sm="4" style="margin-bottom:30px;">
                            <div class="holdW">
                                <Workers name="Kola Adegun" position="CREATIVE DIRECTOR" email="kola@yopmail.com" pic='man3.jpg' />
                            </div>
                        </b-col>
                        
                        <b-col sm="4">
                            <div class="holdW">
                                <Workers name="Mary Nimi" position="CREATIVE DIRECTOR" email="mary@yopmail.com" pic='woman3.jpg' />
                            </div>
                        </b-col>
                        <b-col sm="4">
                            <div class="holdW">
                                <Workers name="Tom Jerry" position="CREATIVE DIRECTOR" email="tom@yopmail.com" pic='man4.jpg' />
                            </div>
                        </b-col>
                        <b-col sm="4">
                            <div class="holdW">
                                <Workers name="Henry Paul" position="CREATIVE DIRECTOR" email="henry@yopmail.com" pic='man5.jpg' />
                            </div>
                        </b-col>
                    </b-row>
                </b-container>
            </div>
        </div>
</template>

<script>
import Workers from './Workers.vue'
export default {
    name : "#people",
    components:{
        Workers
    }
    
}
</script>

<style scoped>
h4{
    text-align: left;
    margin-bottom: 20px;
}
.cateLine{
    text-align: left;
    border-bottom: 2px solid lightgray;
    padding: 5px;
    font-size: 18px;
    font-weight: 600;
    color: gray;
    margin-top: 15px;
}
.cate{
    width: fit-content;
    position: absolute;
}
.all{
    color: #0d6efd;
    font-size: 18px;
    font-weight: 700;
    border-bottom: 2px solid;
    margin-right: 20px;
}
.organ{
    font-size: 18px;
    font-weight: 700;
    color: gray;
}
.searchDiv{
    margin: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.holdSearch{
    display: flex;
    width: 100%;
    border: 1px solid lightgray;
    border-radius: 5px;
    padding: 4px;
    background-color: white;
    height: 40px;
}
.searchinner{
    width: 100%;
    border: none;
    outline: none;
    margin-left: 10px;
}
.holdFilter{
    display: flex;
    justify-content: flex-end;
    align-items: center;
    margin-top: 40px;
    margin-bottom: 30px;
}
#filters{
    border:1px solid lightgray;
    outline: none;
}
.holdW{
    background-color: white;
    border: 1px solid rgb(235, 235, 235);
    border-radius: 5px;
    padding: 10px;
}

.holdW:hover{
    border-bottom: 5px solid rgb(235, 235, 235);
    border-radius: 10px;
    padding: 10px;
}
</style>