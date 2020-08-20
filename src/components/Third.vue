<template>
    <div class="container-fluid">
        <div class="container1">
            <h1 class="op">PROJECTS</h1>
        <div class="row">
            <div class="col left sm">
                <div class="left">
                    <img class="test1" src="../assets/coder1.gif"/>
                </div>
            </div>
            <div class="col left">
                <div id="carouselExampleInterval" class="carousel slide" data-ride="carousel">
                    <div class="carousel-inner">
                        <div class="carousel-item active" data-interval="2000">
                            <div class="card">
                                <img src="../assets/banka.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Ba₦ka</h5>
                                    <p class="card-text">A banking Application.</p>
                                </div>
                            </div> 
                        </div>
                        <div class="carousel-item" data-interval="2000">
                            <div class="card">
                                <img src="../assets/portfolio.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Portfolio</h5>
                                    <p class="card-text">My portfolio built with Vue.</p>
                                </div>
                            </div> 
                        </div>
                        <div class="carousel-item" data-interval="2000">
                            <div class="card">
                                <img src="../assets/paycenter.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">PayCentre Africa</h5>
                                    <p class="card-text">An agency banking company.</p>
                                </div>
                            </div> 
                        </div>
                        <div class="carousel-item" data-interval="2000">
                            <div class="card">
                                <img src="../assets/zasby.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Zasby Travels</h5>
                                    <p class="card-text">A travel agency company.</p>
                                </div>
                            </div> 
                        </div>
                        <div class="carousel-item" data-interval="2000">
                            <div class="card">
                                <img src="../assets/bookit.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Bookit</h5>
                                    <p class="card-text">A ticket booking platform.</p>
                                </div>
                            </div> 
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#carouselExampleInterval" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#carouselExampleInterval" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
            </div>
        </div>
        </div>
    </div>            
</template>



<script>
export default {
    name:'Third',
}
</script>

<style scoped>
.left{
    margin: auto;
}
.op{
    text-align:center;
    color:#0066F5;
    letter-spacing: 0.22em;
text-decoration-line: underline;
font-weight: 900;
line-height: 34px;
}
</style>