<template>
    <div id="map"></div>
</template>
<script>
import 'leaflet/dist/leaflet-src';
import * as L from 'leaflet'
export default {
    mounted(){
    var map = L.map('map').setView([51.505, -0.09], 13);
    }
}
</script>
<style>
#map {
    height: 90vh;    
}
</style>