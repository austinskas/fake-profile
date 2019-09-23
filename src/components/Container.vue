<template>

        <div class="containers">
            <div class="projects-title">
            <h2>Projektai</h2>
            </div>
            <div class="container-small">
                <div class="container-inside"></div>
                <h5>Web Design Sample</h5>
            </div>
            <div class="container-small">
                <div class="container-inside2">
                </div>
                <h5>Web Design Sample</h5>
            </div>
            <div class="container-small">
                <div class="container-inside3"></div>
                <h5>Web Design Sample</h5>
            </div>
        </div>       
     
</template>

<script>

export default {
    name: 'Container',

}
</script>

<style>
.projects-title {
margin-left: 50px;
}

.containers {
    width: 100vw;
	max-width: 100%;
	overflow: hidden;
    margin: 0 auto;
	padding-top: 50px;
     height: 640px;
}

.container-small {
    background-color: #3252E5;
    width: 290px;
    height: 373px;
    margin-right: 50px;
    margin-top: 30px;
    margin-left: 110px;
    text-align: center;
	display: inline-block;
    color: white;
}

.container-inside {
    background-color: white;
    width: 242px;
    height: 256px;
    display: inline-block;
    margin-top: 30px;
    content:url(https://www.eye-catchy.com/wp-content/uploads/2016/10/Web-Design-Sample-23.jpg);

}


.container-inside2 {
    background-color: white;
    width: 242px;
    height: 256px;
    display: inline-block;
    margin-top: 30px;
    content:url(https://www.eye-catchy.com/wp-content/uploads/2016/10/Web-Design-Sample-9.jpg);

}


.container-inside3 {
    background-color: white;
    width: 242px;
    height: 256px;
    display: inline-block;
    margin-top: 30px;
    content:url(https://www.eye-catchy.com/wp-content/uploads/2016/10/Web-Design-Sample-1.jpeg);

}

</style>