<template>
    <div id="app">
        <b-container fluid>
            <b-row>
                <b-col id="nav" cols="3" style="border: solid 1px red">


                    <b-row>
                        <b-col cols="12">
                            <b-input></b-input>
                        </b-col>
                    </b-row>
                    <b-nav vertical align="center"  tabs>
                        <b-nav-item to="#" >test</b-nav-item>
                        <b-nav-item to="#" >test</b-nav-item>
                        <b-nav-item to="#" >test</b-nav-item>
                        <b-nav-item to="#" >test</b-nav-item>
                        <b-nav-item to="#" >test</b-nav-item>
                        <b-nav-item to="#" >test</b-nav-item>
                        <b-nav-item to="#" >test</b-nav-item>
                        <b-nav-item to="#" >test</b-nav-item>
                        <b-nav-item to="#" >test</b-nav-item>
                        <b-nav-item to="#" >test</b-nav-item>
                    </b-nav>
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

    #nav {
        min-height: 500px;
    }

    .tab-content {
        border: solid 1px red;
        display: none;
    }
</style>
