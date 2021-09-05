<template>
    <div id="groWorker">
        <div class="h2 mb-0 circle">
            <b-icon class="h5 mb-2" icon="exclamation-circle" variant="secondary"></b-icon>
        </div>
        <div>
            <img class="creativeImage" :src="require('@/assets/' + pic + '')" alt="" />
            <h4>{{ name }}</h4>
            <p>{{ position }}</p>
        </div>
        <div class="holdRating">
            <div><b-icon class="h5 mb-2" icon="clock" variant="secondary"></b-icon></div>
            <div class="ratePer">
                <div class="holdOut1">
                   <div class="rateInner1"></div> 
                </div>
                <div class="holdOut2">
                   <div class="rateInner2"></div> 
                </div>
                <div class="holdOut3">
                   <div class="rateInner3"></div> 
                </div>
            </div>
            <div>
                <p>63%</p>
            </div>
        </div>
        <div class="email">
            <p>{{ email }}</p>
        </div>        
    </div>
</template>

<script>
export default {
    name: "Workers",
    props:{
        name:{
            type: String,
        },
        position:{
            type: String,
        },
        pic:{
            type: String,
            default: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTEpOB50Gf-839DMNoHRlYYBAWP0TN73RHsGg&usqp=CAU"
        },
        email:{
            type:String
        }
    }
}
</script>

<style scoped>
.circle{
    text-align: right;
    margin-right: 10px;
}
.creativeImage{
    width: 100px;
    height: 100px;
    border: 3px solid blue;
    border-radius: 50%;
    margin-bottom: 20px;
}
.holdRating{
    display: flex;
    justify-content: space-around;
}
.ratePer{
    display: flex;
    justify-content: space-between;
    margin-top: 7px;
}
.rateInner1{
    width: 30px;
    height: 10px;
    background-color: blue;
    border-radius: 50px;
    margin-right: 5px;
}
.rateInner2{
    width: 30px;
    height: 10px;
    background-color: rgba(54, 54, 252, 0.842);
    border-radius: 50px;
    margin-right: 5px;
}
.rateInner3{
    width: 13px;
    height: 10px;
    background-color: rgba(102, 191, 250, 0.856);
    border-radius: 50px;
}
.holdOut1{
    width: 30px;
    height: 10px;
    background-color: #d8d8d8;
    border-radius: 50px;
    margin-right: 5px;
}
.holdOut2{
    width: 30px;
    height: 10px;
    background-color: #d8d8d8;
    border-radius: 50px;
    margin-right: 5px;
}
.holdOut3{
    width: 30px;
    height: 10px;
    background-color: #d8d8d8;
    border-radius: 50px;
}
.email{
    border-top: 1px solid lightgray;
}
</style>