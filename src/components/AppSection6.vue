<script>
export default{
    name: `AppSection6`
}
</script>

<template>
    <section>
        <h2>Pricing Plans</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>

        <!-- Tabella -->
        <div class="container disp_flex">
            <!-- Colonna 1 -->
            <div class="col">
                <div class="choiced_item_bar"></div>
                <div class="board_cell">
                    <div class="board_cell_title"></div>
                    <div class="board_cell_title">
                        <h3>Save up to 40% by paying weekly</h3>
                    </div>
                </div>
                <div class="board_cell">
                    <span class="">Number of courses</span>
                </div>
                <div class="board_cell">
                    <span class="">Time</span>
                </div>
                <div class="board_cell">
                    <span class="">Web designing</span>
                </div>
                <div class="board_cell">
                    <span class="">Human-Centered Design</span>
                </div>
                <div class="board_cell">
                    <span class="">Basic Marketing</span>
                </div>
                <div class="board_cell">
                    <span class="">Python for Everybody</span>
                </div>
                <div class="board_cell">
                    <span class="">Android developer</span>
                </div>
                <div class="board_cell">
                    <span class="">Business English</span>
                </div>
            </div>

            <!-- Colonna 2 -->
             <div class="col">
                <div class="choiced_item_bar"></div>
                <div class="board_cell">
                    <div class="board_cell_title">
                        <img src="../assets/h5-custom-icon-7.png" alt="">
                    </div>
                    <div class="board_cell_title">
                        <h3>Standard</h3>
                        <h3>$12</h3>
                    </div>
                </div>
                <div class="board_cell">
                    <span class="">2</span>
                </div>
                <div class="board_cell">
                    <span class="">15 days</span>
                </div>
                <div class="board_cell">
                    <span class=""><i class="fa-solid fa-check"></i></span>
                </div>
                <div class="board_cell">
                    <span class=""><i class="fa-solid fa-check"></i></span>
                </div>
                <div class="board_cell">
                    <span class=""><i class="fa-sharp fa-solid fa-xmark"></i></span>
                </div>
                <div class="board_cell">
                    <span class=""><i class="fa-sharp fa-solid fa-xmark"></i></span>
                </div>
                <div class="board_cell">
                    <span class=""><i class="fa-sharp fa-solid fa-xmark"></i></span>
                </div>
                <div class="board_cell">
                    <span class=""><i class="fa-sharp fa-solid fa-xmark"></i></span>
                </div>
                <div class="board_cell">
                    <button class="price_button">
                        GET IT NOW
                    </button>
                </div>
            </div>

            <!-- Colonna 3 -->
            <div class="col">
                <div class="choiced_item_bar"></div>
                <div class="board_cell">
                    <div class="board_cell_title">
                        <img src="../assets/h5-custom-icon-8.png" alt="">
                    </div>
                    <div class="board_cell_title">
                        <h3>Professional</h3>
                        <h3>$59</h3>
                    </div>
                </div>
                <div class="board_cell">
                    <span class="">4</span>
                </div>
                <div class="board_cell">
                    <span class="">30 days</span>
                </div>
                <div class="board_cell">
                    <span class=""><i class="fa-solid fa-check"></i></span>
                </div>
                <div class="board_cell">
                    <span class=""><i class="fa-solid fa-check"></i></span>
                </div>
                <div class="board_cell">
                    <span class=""><i class="fa-solid fa-check"></i></span>
                </div>
                <div class="board_cell">
                    <span class=""><i class="fa-solid fa-check"></i></span>
                </div>
                <div class="board_cell">
                    <span class=""><i class="fa-sharp fa-solid fa-xmark"></i></span>
                </div>
                <div class="board_cell">
                    <span class=""><i class="fa-sharp fa-solid fa-xmark"></i></span>
                </div>
                <div class="board_cell">
                    <button class="active_button">
                        GET IT NOW
                    </button>
                </div>
            </div>

            <!-- Colonna 4 -->
            <div class="col">
                <div class="choiced_item_bar"></div>
                <div class="board_cell">
                    <div class="board_cell_title">
                        <img src="../assets/h5-custom-icon-9.png" alt="">
                    </div>
                    <div class="board_cell_title">
                        <h3>Advanced</h3>
                        <h3>$88</h3>
                    </div>
                </div>
                <div class="board_cell">
                    <span class="">6</span>
                </div>
                <div class="board_cell">
                    <span class="">30 days</span>
                </div>
                <div class="board_cell">
                    <span class=""><i class="fa-solid fa-check"></i></span>
                </div>
                <div class="board_cell">
                    <span class=""><i class="fa-solid fa-check"></i></span>
                </div>
                <div class="board_cell">
                    <span class=""><i class="fa-solid fa-check"></i></span>
                </div>
                <div class="board_cell">
                    <span class=""><i class="fa-solid fa-check"></i></span>
                </div>
                <div class="board_cell">
                    <span class=""><i class="fa-solid fa-check"></i></span>
                </div>
                <div class="board_cell">
                    <span class=""><i class="fa-solid fa-check"></i></span>
                </div>
                <div class="board_cell">
                    <button class="price_button">
                        GET IT NOW
                    </button>
                </div>
            </div>
            


        </div>
    </section>
</template>

<style scoped>
.col{
    width: calc(100% / 4);
    color: gray;
}
.col h3{
    color: black;
}
.choiced_item_bar{
    height: 3px;
    background-color: lightblue;
}
.board_cell{
    border-bottom: 1px solid lightgray;
    border-left: 1px solid lightgray;
    border-right: 1px solid lightgray;
    padding: 10px;
    text-align: center;
}
.board_cell_title{
    height: 100px;
    padding: 10px;
}
.fa-check{
    color: lightblue;
}
.price_button{
    padding: 10px 20px;
    border: 1px solid lightgray;
    color: gray;
}
.price_button{
    padding: 10px 20px;
    border: 1px solid lightgray;
    color: white;
    background-color: lightblue;
}
</style>