<template>
    <b-container fluid class="bv-example-row holdHeader">
        <b-row class="text-center">
            <b-col cols="2" class="holdLogo">
                <div class="logo">
                    <span class="logoSmall">NG<sub>EOO</sub></span><span class="logoTest">Test Project</span>
                </div>
            </b-col>
            <b-col cols="7">
                <div class="searchDiv">
                    <div class="holdSearch">
                        <div class="h5 mb-0">
                            <b-icon icon="search" variant="secondary"></b-icon>
                        </div>
                        <input type="text" placeholder="Search" class="searchinner">
                    </div>
                </div>
                
            </b-col>
            <b-col cols="3" class="personOnline">
                <div>
                    <div class="h5 mb-0 bellIcon">
                        <b-icon icon="bell-fill" variant="dark"></b-icon>
                    </div>
                    <div class="num">
                        <span>21</span>
                    </div>
                </div>
                
                <div class="holdImage">
                    <img class="imgDiv" src="https://images.unsplash.com/photo-1593085512500-5d55148d6f0d?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8Y2FydG9vbnxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&w=1000&q=80" alt="">
                    <div>
                        <span class="serah">Hi, Sarah Cody</span>
                    </div>
                </div>
                
            </b-col>
        </b-row>
    </b-container>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.holdHeader{
    border-bottom: 2px solid lightgray;
    padding-bottom: 10px;
    padding-top: 10px;
}
.holdLogo{
    display: flex;
    justify-content: center;
    align-items: center;
}
.logo{
    font-size: 20px;
}
.logoSmall{
    color: green;
    margin: 10px;
}

.logoSmall span{
    color: green;
    margin: 10px;
}
.logoTest{
    font-weight: 700;
}
.holdSearch{
    display: flex;
    width: 100%;
    border: 1px solid lightgray;
    border-radius: 5px;
    padding: 4px;
}
.searchDiv{
    margin: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.searchinner{
    width: 100%;
    border: none;
    outline: none;
    margin-left: 10px;
}
.personOnline{
    display: flex;
    align-items: center;
}

.bellIcon{
    position: absolute;
}
.num{
    position: relative;
    left: 12px;
    top: -7px;
    font-size: 15px;
    background: #23af23;
    height: 15px;
    width: 15px;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    padding: 10px;
}

.imgDiv{
    width: 50px;
    border-radius: 50%;
    margin: 0px 20px;
}

.holdImage{
    display: flex;
    justify-content: center;
    align-items: center;
    margin-left: 20px;
}
.serah{
    font-size: 20px;
    font-weight: 700;
}
</style>