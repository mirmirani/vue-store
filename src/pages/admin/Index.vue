<template>
    <div>
        <div class="admin-new">
            <div class="container">
                <div class="col-lg-3 col-md-3 col-sm-12 col-xs-12">
                    <ul class="admin-menu">
                        <li><router-link to="/admin">View Products</router-link></li>
                        <li><router-link to="/admin">New Product</router-link></li>
                    </ul>
                </div>
                <!--outlet children routes-->
                <router-view></router-view>
            </div>
        </div>
    </div>
</template>
