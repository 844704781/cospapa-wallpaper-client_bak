<template>
    <div id="app">
        <b-container fluid>
            <b-row>
                <b-col id="nav" cols="3" style="border: solid 1px red">
                    <b-row>搜索</b-row>
                    <b-row>全部</b-row>
                    <b-row>喜欢</b-row>
                    <b-row>个人中心</b-row>
                </b-col>
                <b-col id="content" cols="9">
                    <router-view/>
                </b-col>
            </b-row>
        </b-container>
    </div>
</template>

<style>
    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
    }

    #nav{
      min-height: 600px;
    }
</style>
