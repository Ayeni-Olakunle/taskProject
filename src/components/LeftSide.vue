<template>
    <div>
        <div>
            <select name="tean" class="selectTeam">
                <option>Select Team</option>
                <option>FrontEnd Developers</option>
                <option>Back End Developers</option>
                <option>Graphics</option>
                <option>UI/UX Designer</option>
            </select>
        </div><br><br><br>
        <div>
            <h5>Design Team</h5><br>
            <div class="holdCircle">
                <div class="circleIn">
                   <div class="progress pink">
                        <span class="progress-left">
                            <span class="progress-bar"></span>
                        </span>
                        <span class="progress-right">
                            <span class="progress-bar"></span>
                        </span>
                        <div class="progress-value">
                            <p class="perVa">63%</p>
                        </div>
                    </div> 
                </div>
                
            </div>
            
        </div><br><br>

        <div>
            <h5>Projects</h5><br>
            <div>
                <b-container class="bv-example-row" style="border-bottom: 1px solid lightgray; padding-bottom:20px;">
                    <b-row>
                        <b-col sm="6">
                            <div  class="holdCon">
                                <p class="txtInfo">TOTAL</p>
                                <h4 class="txtInfoNum">145</h4>
                            </div>
                        </b-col>
                        <b-col sm="6">
                            <div class="holdCon">
                                <p class="txtInfo">COMPLETED</p>
                                <h4 class="txtInfoNum" style="border-left-color: blue;">115</h4>
                            </div>
                        </b-col><br><br><br>
                        <b-col sm="6">
                            <div  class="holdCon">
                                <p class="txtInfo">IN PROGRESS</p>
                                <h4 class="txtInfoNum" style="border-left-color: green;">20</h4>
                            </div>
                        </b-col>
                        <b-col sm="6">
                            <div class="holdCon">
                                <p class="txtInfo">WAITING</p>
                                <h4 class="txtInfoNum" style="border-left-color: red;">10</h4>
                            </div>
                        </b-col>
                    </b-row>
                </b-container>
            </div>
        </div>
        <div>
            <div class="message">
                <div>
                    <b-icon class="h4 chatIcon" icon="chat-left-fill" variant="light"></b-icon>
                </div>
                <div>
                    <p style="font-size: 15px;margin-bottom: 3px;     margin-top: -10px;">DECLERATION CENTER</p>
                    <select style="border: none;background-color: transparent;font-weight: 700; outline:none;">
                        <option value="">Internal Message</option>
                    </select>
                </div>

            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.selectTeam{
    width: 100%;
    padding: 10px;
    background-color: #0d6efd;
    color: white;
    font-size: 18px;
    font-weight: 400;
    border: none;
    border-radius: 5px;
    outline: none;
}

.progress{
    background: none;
    margin: 0 auto;
    box-shadow: none;
    width: 150px;
    height: 150px;
    line-height: 150px;
    position: relative;
}
.progress:after{
    content: "";
    border-radius: 50%;
    border: 15px solid #f2f5f5;
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
}
.progress > span{
    position: absolute;
    top: 0;
    z-index: 1;
    width: 50%;
    height: 100%;
    overflow: hidden;
}
.progress .progress-left{
    left: 0;
}
.progress .progress-bar{
    border-width: 15px;
    border-style: solid;
    position: absolute;
    width: 100%;
    height: 100%;
    background: none;
    top: 0;
}
.progress .progress-left .progress-bar{
    left: 100%;
    border-top-right-radius: 80px;
    border-bottom-right-radius: 80px;
    border-left: 0;
    -webkit-transform-origin: center left;
    transform-origin: center left;
}
.progress .progress-right{
    right: 0;
}
.progress .progress-right .progress-bar{
    left: -100%;
    -webkit-transform-origin: center right;
    transform-origin: center right;
    border-top-left-radius: 80px;
    border-bottom-left-radius: 80px;
    border-right: 0;
    animation: loading-1 1.8s linear forwards;
}
.progress .progress-value{
    font-size: 24px;
    color: rgb(250, 245, 245);
    text-align: center;
    width: 100%;
    height: 100%;
    position: absolute;
}

@keyframes loading-1{
    0%{
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg);
    }
    100%{
        -webkit-transform: rotate(180deg);
        transform: rotate(180deg);
    }
}
@keyframes loading-2{
    0%{
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg);
    }
    100%{
        -webkit-transform: rotate(144deg);
        transform: rotate(144deg);
    }
}
@keyframes loading-3{
    0%{
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg);
    }
    100%{
        -webkit-transform: rotate(90deg);
        transform: rotate(90deg);
    }
}
@keyframes loading-4{
    0%{
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg);
    }
    100%{
        -webkit-transform: rotate(36deg);
        transform: rotate(36deg);
    }
}
@keyframes loading-5{
    0%{
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg);
    }
    100%{
        -webkit-transform: rotate(126deg);
        transform: rotate(126deg);
    }
}

.progress.pink .progress-bar{
    border-color: #378bf8;
}
.progress.pink .progress-left .progress-bar{
    animation: loading-4 0.4s linear forwards 1.8s;
}

.holdCon{
    width: 100%;
    background-color: #f1f1f1;
    border-radius: 10px;
    padding: 5px 10px;
    margin: 5px 10px;
}
.txtInfo{
    font-size: 10px;
    margin: 5px;
}

.txtInfoNum{
    border-left: 4px solid orange;
    padding: 0px 5px;
}

.message{
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #f1f1f1;
    margin-top: 40px;
    border-radius: 3px;
    padding: 10px;
}

.chatIcon{
    width: 40px;
    height: 40px;
    background-color: #0d6efd;
    padding: 10px;
    border-radius: 3px;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-right: 10px;
}
.holdCircle{
    display: flex;
    justify-content: center;
    align-items: center;

}
.circleIn{
    width: fit-content;
    height: fit-content;
    background-color: #e2e2e2;
    border-radius: 50%;
    padding: 10px;
}
.perVa{
    color: #4e4b4b;
    font-size: 30px;
    font-weight: 800;
}
</style>