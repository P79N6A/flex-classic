<template>
    <div class="doc-box">
        <div class="box1">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
        </div>
        <div class="box2">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
        </div>
        <div class="box3">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
        </div>
        <div class="box4">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
        </div>
        <div class="box5">
            <div class="item">1</div>
            <div class="item">2</div>
            <div class="item">3</div>
            <div class="item">4</div>
        </div>
    </div>
</template>

<style type="text/css" scoped>
    .box1, .box2, .box3, .box4, .box5 {
        margin: 20px auto;
        width: 160px;
        height: 160px;
        border: 1px solid;
    }

    .box1 {
        display: flex;
        flex-direction: row;
        justify-content: flex-start;
    }

    .box2 {
        display: flex;
        flex-direction: row;
        justify-content: center;
    }

    .box3 {
        display: flex;
        flex-direction: row;
        justify-content: flex-end;
    }

    .box4 {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
    }

    .box5 {
        display: flex;
        flex-direction: row;
        justify-content: space-around;
    }
</style>
