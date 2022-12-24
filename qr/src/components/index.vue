<template>
    <div class="back">
        <div class="qr" style="position:relative; top: -16%">
            <img src="../assets/image-qr-code.png" width=250 height=270>
        </div>
        <h1>
            Improve Yout front-end skills by building projects
        </h1>
        <h6>
            scan the QR code to visit Frontent Mentor And Take your coding skills to next level
        </h6>
    </div>

</template>

<script>

</script>
<style>
    .back{
        background: white;
        border-radius: 10px;
        position:relative;
        left: 37%;
        display: flex;
        justify-content: center;
        align-items: center;
        width: 300px;
        height: 450px;
    }
    .qr img{
        width: 250px;
        width: 270px;
        display: flex;
        position: relative;
        background: hsl(0, 0%, 100%);
        border-radius: 10px;
    }
    h1{
        width:250px;
        font-size: 20px;
        font: bold;
        display: inline-flex;
        position: absolute;
        top:65%;
        left:8.5%
    }
    h6{
        width:250px;
        color:hsl(220, 15%, 55%);
        font-size: 12.5px;
        font: bold;
        display: inline-flex;
        position: absolute;
        top:77%;
        left:8.5%

    }
    @media only screen and (max-width: 375px) {
        .back{
            background: white;
            border-radius: 10px;
            position:relative;
            left: 10%;
            display: flex;
            justify-content: center;
            align-items: center;
            width: 300px;
            height: 450px;
        }
    }

</style>