<template>
    <div>
        <div class="p">
            <p>
                Outgoing Payments
                <span>(For 2021)</span>
            </p>
        </div>
        <div class="holdGraph">
            <div class="graphNo">
                <p>250</p>
                <p>200</p>
                <p>150</p>
                <p>100</p>
                <p>0</p>
            </div>
            <div style="width:100%;">
                <div class="graphMon">
                    <div class="holdRange">
                        <div class="rangeIn"></div>
                    </div>
                    <div class="holdRange">
                        <div class="rangeIn" style="height: 170px;"></div>
                    </div>
                    <div class="holdRange">
                        <div class="rangeIn" style="height: 270px;"></div>
                    </div>
                    <div class="holdRange">
                        <div class="rangeIn" style="height: 200px;"></div>
                    </div>
                    <div class="holdRange">
                        <div class="rangeIn" style="height: 90px;"></div>
                    </div>
                    <div class="holdRange">
                        <div class="rangeIn" style="height: 270px;"></div>
                    </div>
                    <div class="holdRange">
                        <div class="rangeIn" style="height: 370px;"></div>
                    </div>
                    <div class="holdRange">
                        <div class="rangeIn" style="height: 190px;"></div>
                    </div>
                    <div class="holdRange">
                        <div class="rangeIn" style="height: 220px;"></div>
                    </div>
                    <div class="holdRange">
                        <div class="rangeIn" style="height: 150px;"></div>
                    </div>
                </div>
                
                <div class="mont">
                    <p>Jan</p>
                    <p>Feb</p>
                    <p>Mar</p>
                    <p>May</p>
                    <p>Jun</p>
                    <p>Jul</p>
                    <p>Aug</p>
                    <p>Sep</p>
                    <p>Oct</p>
                    <p>Nov</p>
                    <p>Dec</p>
                </div>
            </div>
        </div>
        
            <div class="holdGraph" style="flex-direction: column;">
                <div class="tabl">
                    <p>My Transcations</p>
                    <p class="see">Sell All ></p>
                </div>
                <table>
                    <thead>
                        <th></th>
                        <th>Date</th>
                        <th>RerenceID</th>
                        <th>Beneficiary</th>
                        <th>Remarks</th>
                        <th>Amounts</th>
                        <th>Status</th>
                    </thead>
                    <tbody>
                        <tr style="font-size: 15px;color: gray;">
                            <td>
                                <div class="h5 mb-0">
                                    <b-icon icon="clock-history" variant="secondary"></b-icon>
                                 </div>
                            </td>
                            <td>5/9/2021</td>
                            <td>1234565432167</td>
                            <td>Sarah Bright</td>
                            <td>Lundry</td>
                            <td>10,000</td>
                            <td style="color: blue;">Pending</td>
                        </tr>
                        <tr style="font-size: 15px;color: gray;">
                            <td>
                                <div class="h5 mb-0">
                                    <b-icon icon="clock-history" variant="secondary"></b-icon>
                                 </div>
                            </td>
                            <td>5/9/2021</td>
                            <td>1234565432167</td>
                            <td>Sarah Bright</td>
                            <td>Lundry</td>
                            <td>10,000</td>
                            <td style="color: blue;">Pending</td>
                        </tr>
                        <tr style="font-size: 15px;color: gray;">
                            <td>
                                <div class="h5 mb-0">
                                    <b-icon icon="clock-history" variant="secondary"></b-icon>
                                 </div>
                            </td>
                            <td>5/9/2021</td>
                            <td>1234565432167</td>
                            <td>Sarah Bright</td>
                            <td>Lundry</td>
                            <td>10,000</td>
                            <td style="color: blue;">Pending</td>
                        </tr>
                        <tr style="font-size: 15px;color: gray;">
                            <td>
                                <div class="h5 mb-0">
                                    <b-icon icon="clock-history" variant="secondary"></b-icon>
                                 </div>
                            </td>
                            <td>5/9/2021</td>
                            <td>1234565432167</td>
                            <td>Sarah Bright</td>
                            <td>Lundry</td>
                            <td>10,000</td>
                            <td style="color: blue;">Pending</td>
                        </tr>
                        <tr style="font-size: 15px;color: gray;">
                            <td>
                                <div class="h5 mb-0">
                                    <b-icon icon="clock-history" variant="secondary"></b-icon>
                                 </div>
                            </td>
                            <td>5/9/2021</td>
                            <td>1234565432167</td>
                            <td>Sarah Bright</td>
                            <td>Lundry</td>
                            <td>10,000</td>
                            <td style="color: blue;">Pending</td>
                        </tr>
                        <tr style="font-size: 15px;color: gray;">
                            <td>
                                <div class="h5 mb-0">
                                    <b-icon icon="clock-history" variant="secondary"></b-icon>
                                 </div>
                            </td>
                            <td>5/9/2021</td>
                            <td>1234565432167</td>
                            <td>Sarah Bright</td>
                            <td>Lundry</td>
                            <td>10,000</td>
                            <td style="color: blue;">Pending</td>
                        </tr>
                    </tbody>
                </table>  
            </div>
    </div>
</template>

<script>
export default {
    data() {
      return {
        items: [
          { age: 40, first_name: 'Dickerson', last_name: 'Macdonald', },
          { age: 21, first_name: 'Larsen', last_name: 'Shaw' },
          { age: 89, first_name: 'Geneva', last_name: 'Wilson' },
          { age: 38, first_name: 'Jami', last_name: 'Carney' }
        ]
      }
    }
}
</script>

<style scoped>
.holdGraph{
    display: flex;
    background: white;
    padding: 10px;
    border-radius: 5px;
    border: 1px solid #e0e0e0;
    margin: 20px 0px;
}
.graphNo{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    text-align: end;
}

.graphMon{
    width: 100%;
    height: 400px;
    border: 1px solid lightgrey;
    border-top: none;
    border-right: none;
    display: flex;
    justify-content: space-around;
}

.mont{
    display: flex;
    justify-content: space-around;
    width: 100%;
}
.holdRange{
    width: 10px;
    height: 400px;
    background: #edf4ff;
    border-radius: 50px;
    display: flex;
    justify-content: center;
    align-items: end;
}
.rangeIn{
    width: 10px;
    background: blue;
    height: 100px;
    border-radius: 50px;
}
.p{
    margin-top: 30px;
    text-align: left;
    font-size: 20px;
    font-weight: 700;
}

.tabl{
    display: flex;
    justify-content: space-between;
    font-size: 17px;
    border-bottom: 1px solid lightgray;
    margin-bottom: 30px;
}

.see{
    color: blue;
    font-weight: 600;
}
</style>