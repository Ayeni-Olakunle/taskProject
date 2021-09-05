<template>
    <div>
        <div class="holdImage">
            <img class="imgDiv" src="https://images.unsplash.com/photo-1593085512500-5d55148d6f0d?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8Y2FydG9vbnxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&w=1000&q=80" alt="">
                <div>
                     <p class="serah">Hi, Sarah Cody</p>
                     <p class="email">serah@gmail.com</p>
                </div>
        </div>
        <ul class="listOne">
            <li><b-icon icon="house-door" variant="secondary"></b-icon> <a href="/dashboard">Dashboard</a></li>
            <li><b-icon icon="chat-dots" variant="secondary"></b-icon> <a href="#">People</a></li>
            <li><b-icon icon="people" variant="secondary"></b-icon> <a href="#">Uers Group</a></li>
            <li><b-icon icon="people" variant="secondary"></b-icon> <a href="#">Transcations</a></li>
        </ul>
        <ul class="listOne" style="border: none;">
            <li> <b-icon icon="gear" aria-hidden="true"></b-icon> <a href="#">Settin</a></li>
            <li><b-icon icon="key" variant="secondary"></b-icon> <a href="#">API Keys</a></li>
            <li><b-icon icon="box-arrow-right" variant="secondary"></b-icon> <a href="#">Logout</a></li>
        </ul>
        <div class="topUp">
            <div class="arro"><b-icon icon="arrow-up" variant="primary" class="arroKo"></b-icon></div>
            <span>Top up</span>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>

<style scoped>
.holdImage{
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 10px;
    margin-left: 0;
    margin: 30px 0px;
}
.imgDiv{
    width: 50px;
    border-radius: 50%;
    margin: 0px 10px;
}
.serah{
    margin-bottom: 0;
    font-size: 15px;
    font-weight: 700;
}

.email{
    margin-bottom: 0;
    font-size: 15px;
}
.listOne{
    text-align: left;
    border-bottom: 1px solid lightgray;
    list-style: none;
    padding-left: 1rem !important;
}
li{
    font-size: 18px;
    padding: 10px;
}

li a{
    padding: 10px;
    text-decoration: none;
    color: rgb(167, 167, 167);
}

li:hover{
    width: 100%;
    background: rgb(240, 240, 240);
    border-radius: 5px;
}
li a:hover{
    color: black;
}
li:last-child{
    margin-bottom: 20px;
}

.topUp{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    padding: 10px;
    background-color: #0d6efd;
    border-radius: 5px;
    margin-bottom: 10px;
    color: white;
}

.arro{
    width: 40px;
    height: 40px;
    background-color: white;
    padding: 10px;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-right: 10px;
}
</style>