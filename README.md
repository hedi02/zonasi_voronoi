# zonasi_voronoi
Mathematically fair school zoning


<!DOCTYPE html>
<head>    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.4.0/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.4.0/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://rawcdn.githack.com/python-visualization/folium/master/folium/templates/leaflet.awesome.rotate.css"/>
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_5e76493185984f9cbfb9a9690f6cded8 {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
            </style>
        
</head>
<body>    
    
            <div class="folium-map" id="map_5e76493185984f9cbfb9a9690f6cded8" ></div>
        
</body>
<script>    
    
            var map_5e76493185984f9cbfb9a9690f6cded8 = L.map(
                "map_5e76493185984f9cbfb9a9690f6cded8",
                {
                    center: [-7.8022, 110.3679],
                    crs: L.CRS.EPSG3857,
                    zoom: 13,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_912ef5bd697b487e82174875e3184f1d = L.tileLayer(
                "https://cartodb-basemaps-{s}.global.ssl.fastly.net/light_all/{z}/{x}/{y}.png",
                {"attribution": "\u0026copy; \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eOpenStreetMap\u003c/a\u003e contributors \u0026copy; \u003ca href=\"http://cartodb.com/attributions\"\u003eCartoDB\u003c/a\u003e, CartoDB \u003ca href =\"http://cartodb.com/attributions\"\u003eattributions\u003c/a\u003e", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
            var marker_8297edbe92184164a8d4c8fe7b98ed6f = L.marker(
                [-7.6992, 110.4054],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_028dc84ebaf94da8b6e090f3000753b3 = L.popup({"maxWidth": "100%"});

        
            var html_b22b64683e044f928267b16b5f0b0c4f = $(`<div id="html_b22b64683e044f928267b16b5f0b0c4f" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 NGAGLIK</div>`)[0];
            popup_028dc84ebaf94da8b6e090f3000753b3.setContent(html_b22b64683e044f928267b16b5f0b0c4f);
        

        marker_8297edbe92184164a8d4c8fe7b98ed6f.bindPopup(popup_028dc84ebaf94da8b6e090f3000753b3)
        ;

        
    
    
            var marker_fc895f0c0ad94b818903ee1c95172ad2 = L.marker(
                [-7.7393, 110.4744],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_177d56a3617649e1b0ea2f2557273eef = L.popup({"maxWidth": "100%"});

        
            var html_8de216a2537b4a87bac7ac2f59356cd5 = $(`<div id="html_8de216a2537b4a87bac7ac2f59356cd5" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 KALASAN</div>`)[0];
            popup_177d56a3617649e1b0ea2f2557273eef.setContent(html_8de216a2537b4a87bac7ac2f59356cd5);
        

        marker_fc895f0c0ad94b818903ee1c95172ad2.bindPopup(popup_177d56a3617649e1b0ea2f2557273eef)
        ;

        
    
    
            var marker_e57598d4ae4845da8cb60d3e86d0f667 = L.marker(
                [-7.8036, 110.6747],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_11e2564749344eceacc7aa50dada7d5f = L.popup({"maxWidth": "100%"});

        
            var html_c044b46495fb4bfcb2fb7954172715a2 = $(`<div id="html_c044b46495fb4bfcb2fb7954172715a2" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 NGAWEN</div>`)[0];
            popup_11e2564749344eceacc7aa50dada7d5f.setContent(html_c044b46495fb4bfcb2fb7954172715a2);
        

        marker_e57598d4ae4845da8cb60d3e86d0f667.bindPopup(popup_11e2564749344eceacc7aa50dada7d5f)
        ;

        
    
    
            var marker_39479c020b924215b2b7eb143e13c11c = L.marker(
                [-7.925268300000001, 110.5634617],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_ef97837166144635b3f2e6c549bb5c8c = L.popup({"maxWidth": "100%"});

        
            var html_4ffa3a3fc13042af9aec326fb5ae70d3 = $(`<div id="html_4ffa3a3fc13042af9aec326fb5ae70d3" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 PLAYEN</div>`)[0];
            popup_ef97837166144635b3f2e6c549bb5c8c.setContent(html_4ffa3a3fc13042af9aec326fb5ae70d3);
        

        marker_39479c020b924215b2b7eb143e13c11c.bindPopup(popup_ef97837166144635b3f2e6c549bb5c8c)
        ;

        
    
    
            var marker_5ba2cdd45a5c4433b64e00ea3cef0351 = L.marker(
                [-7.8982, 110.166],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_8e566f180f6042129c27ff421f2b086d = L.popup({"maxWidth": "100%"});

        
            var html_ec8e1172d9fc4976a61801b503c671f0 = $(`<div id="html_ec8e1172d9fc4976a61801b503c671f0" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 PANJATAN</div>`)[0];
            popup_8e566f180f6042129c27ff421f2b086d.setContent(html_ec8e1172d9fc4976a61801b503c671f0);
        

        marker_5ba2cdd45a5c4433b64e00ea3cef0351.bindPopup(popup_8e566f180f6042129c27ff421f2b086d)
        ;

        
    
    
            var marker_1b1380104b6d4f73bd21a706160ba883 = L.marker(
                [-7.8022, 110.3679],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_307280d14afb4b83bb986866ff53ebf3 = L.popup({"maxWidth": "100%"});

        
            var html_e9568d3ad43d4596bf8c9388780dc70c = $(`<div id="html_e9568d3ad43d4596bf8c9388780dc70c" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 YOGYAKARTA</div>`)[0];
            popup_307280d14afb4b83bb986866ff53ebf3.setContent(html_e9568d3ad43d4596bf8c9388780dc70c);
        

        marker_1b1380104b6d4f73bd21a706160ba883.bindPopup(popup_307280d14afb4b83bb986866ff53ebf3)
        ;

        
    
    
            var marker_30a2f4c7a3eb4df6adad3593ea1fe317 = L.marker(
                [-7.941368300000001, 110.2095933],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_df70b0b8e3e44e77bbbce28e9663fe58 = L.popup({"maxWidth": "100%"});

        
            var html_64709cee075d4fdaa3a574be41c43a5a = $(`<div id="html_64709cee075d4fdaa3a574be41c43a5a" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 GALUR</div>`)[0];
            popup_df70b0b8e3e44e77bbbce28e9663fe58.setContent(html_64709cee075d4fdaa3a574be41c43a5a);
        

        marker_30a2f4c7a3eb4df6adad3593ea1fe317.bindPopup(popup_df70b0b8e3e44e77bbbce28e9663fe58)
        ;

        
    
    
            var marker_0deeb513d508428bbcbe3f866b3bc008 = L.marker(
                [-8.0258383, 110.37668329999998],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_e9af9b5d41e74c7285ff641a20b56f9c = L.popup({"maxWidth": "100%"});

        
            var html_e7f36a1f10d64833aa69ceebcdab07ad = $(`<div id="html_e7f36a1f10d64833aa69ceebcdab07ad" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 PURWOSARI</div>`)[0];
            popup_e9af9b5d41e74c7285ff641a20b56f9c.setContent(html_e7f36a1f10d64833aa69ceebcdab07ad);
        

        marker_0deeb513d508428bbcbe3f866b3bc008.bindPopup(popup_e9af9b5d41e74c7285ff641a20b56f9c)
        ;

        
    
    
            var marker_685f47d5857c4bccb3f22b09b51b8096 = L.marker(
                [-7.6821410000000006, 110.357826],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_e396a5ff86aa46ed9783407ad4bb6992 = L.popup({"maxWidth": "100%"});

        
            var html_7bdd2c552d21499bb416cf42eb20b4db = $(`<div id="html_7bdd2c552d21499bb416cf42eb20b4db" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 SLEMAN</div>`)[0];
            popup_e396a5ff86aa46ed9783407ad4bb6992.setContent(html_7bdd2c552d21499bb416cf42eb20b4db);
        

        marker_685f47d5857c4bccb3f22b09b51b8096.bindPopup(popup_e396a5ff86aa46ed9783407ad4bb6992)
        ;

        
    
    
            var marker_273024fdc14b406387ccc132e7af78ba = L.marker(
                [-7.8502, 110.682],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_1af60be69f4a4c3c9664cb8d19bd9c84 = L.popup({"maxWidth": "100%"});

        
            var html_7300223ad04743d6927d81d7e5233bc2 = $(`<div id="html_7300223ad04743d6927d81d7e5233bc2" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 NGAWEN</div>`)[0];
            popup_1af60be69f4a4c3c9664cb8d19bd9c84.setContent(html_7300223ad04743d6927d81d7e5233bc2);
        

        marker_273024fdc14b406387ccc132e7af78ba.bindPopup(popup_1af60be69f4a4c3c9664cb8d19bd9c84)
        ;

        
    
    
            var marker_57bde3b9763f4378bb7edcc4d3140934 = L.marker(
                [-7.7869, 110.3757],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_19ac9e512a6845e18ee8795697e3fd88 = L.popup({"maxWidth": "100%"});

        
            var html_7895366848df44a8a5c21c8eaddb1b4b = $(`<div id="html_7895366848df44a8a5c21c8eaddb1b4b" style="width: 100.0%; height: 100.0%;">SMP NEGERI 5 YOGYAKARTA</div>`)[0];
            popup_19ac9e512a6845e18ee8795697e3fd88.setContent(html_7895366848df44a8a5c21c8eaddb1b4b);
        

        marker_57bde3b9763f4378bb7edcc4d3140934.bindPopup(popup_19ac9e512a6845e18ee8795697e3fd88)
        ;

        
    
    
            var marker_a2c5f67af6354e289abea5df02eb2a10 = L.marker(
                [-7.85585, 110.15644669999999],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_a36f1aaae8c647ff8e5778315280df43 = L.popup({"maxWidth": "100%"});

        
            var html_30df2fae53f1425690c1bc4a50fd5a3e = $(`<div id="html_30df2fae53f1425690c1bc4a50fd5a3e" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 WATES</div>`)[0];
            popup_a36f1aaae8c647ff8e5778315280df43.setContent(html_30df2fae53f1425690c1bc4a50fd5a3e);
        

        marker_a2c5f67af6354e289abea5df02eb2a10.bindPopup(popup_a36f1aaae8c647ff8e5778315280df43)
        ;

        
    
    
            var marker_d13e4f4380a440bfa112d73e5889ffff = L.marker(
                [-7.9585492, 110.3320453],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_6111884dc7ac4a3099c9ae5ffa3e09cf = L.popup({"maxWidth": "100%"});

        
            var html_2b847f188b7c4b0bb7e0a1c914e6a44e = $(`<div id="html_2b847f188b7c4b0bb7e0a1c914e6a44e" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 PUNDONG</div>`)[0];
            popup_6111884dc7ac4a3099c9ae5ffa3e09cf.setContent(html_2b847f188b7c4b0bb7e0a1c914e6a44e);
        

        marker_d13e4f4380a440bfa112d73e5889ffff.bindPopup(popup_6111884dc7ac4a3099c9ae5ffa3e09cf)
        ;

        
    
    
            var marker_f3d44a5c04344ca593e53aafa8d8a774 = L.marker(
                [-7.8295, 110.4119],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_e42d3fd4da67461ea29d3ea217151499 = L.popup({"maxWidth": "100%"});

        
            var html_ac063438ab66478092fdc05f58374605 = $(`<div id="html_ac063438ab66478092fdc05f58374605" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 BANGUNTAPAN</div>`)[0];
            popup_e42d3fd4da67461ea29d3ea217151499.setContent(html_ac063438ab66478092fdc05f58374605);
        

        marker_f3d44a5c04344ca593e53aafa8d8a774.bindPopup(popup_e42d3fd4da67461ea29d3ea217151499)
        ;

        
    
    
            var marker_8de29d023e634dfab676b9061837c478 = L.marker(
                [-7.7604, 110.3856],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_685c02f1ebd042c7abc592483c336bc7 = L.popup({"maxWidth": "100%"});

        
            var html_b6b0f74dedcd4f879921657701dc303a = $(`<div id="html_b6b0f74dedcd4f879921657701dc303a" style="width: 100.0%; height: 100.0%;">SMP NEGERI 5 DEPOK</div>`)[0];
            popup_685c02f1ebd042c7abc592483c336bc7.setContent(html_b6b0f74dedcd4f879921657701dc303a);
        

        marker_8de29d023e634dfab676b9061837c478.bindPopup(popup_685c02f1ebd042c7abc592483c336bc7)
        ;

        
    
    
            var marker_4f0d4ab9bd104178a92d5c2ec715bcb8 = L.marker(
                [-8.0969, 110.66799999999999],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_d01dc0ea2df949068a6434c650958f90 = L.popup({"maxWidth": "100%"});

        
            var html_eb6cac58eac14d2397863e0a0d236790 = $(`<div id="html_eb6cac58eac14d2397863e0a0d236790" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 TEPUS</div>`)[0];
            popup_d01dc0ea2df949068a6434c650958f90.setContent(html_eb6cac58eac14d2397863e0a0d236790);
        

        marker_4f0d4ab9bd104178a92d5c2ec715bcb8.bindPopup(popup_d01dc0ea2df949068a6434c650958f90)
        ;

        
    
    
            var marker_14e4d976572247958fd3f241e396afbc = L.marker(
                [-7.7074, 110.4654],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_e16fa8b6ece741709676ff0ff1b8c079 = L.popup({"maxWidth": "100%"});

        
            var html_c431f4bae3c54b198b22f9dcdb486b0b = $(`<div id="html_c431f4bae3c54b198b22f9dcdb486b0b" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 NGEMPLAK</div>`)[0];
            popup_e16fa8b6ece741709676ff0ff1b8c079.setContent(html_c431f4bae3c54b198b22f9dcdb486b0b);
        

        marker_14e4d976572247958fd3f241e396afbc.bindPopup(popup_e16fa8b6ece741709676ff0ff1b8c079)
        ;

        
    
    
            var marker_af0b6a0e6ded458081254cd4fb095d44 = L.marker(
                [-7.6640083, 110.30819170000001],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_fc59326ae8af49b0b2faf3ffdb98bb79 = L.popup({"maxWidth": "100%"});

        
            var html_313b4ffc121f4677a97551e74f7e24ff = $(`<div id="html_313b4ffc121f4677a97551e74f7e24ff" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 TEMPEL</div>`)[0];
            popup_fc59326ae8af49b0b2faf3ffdb98bb79.setContent(html_313b4ffc121f4677a97551e74f7e24ff);
        

        marker_af0b6a0e6ded458081254cd4fb095d44.bindPopup(popup_fc59326ae8af49b0b2faf3ffdb98bb79)
        ;

        
    
    
            var marker_186e8c8be339456cba7144fb8f515383 = L.marker(
                [-7.8356, 110.4507],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_a0f35d8b30304b0ab964bf20d6ac9d6a = L.popup({"maxWidth": "100%"});

        
            var html_687d6fab4136466da326eef65a2a044a = $(`<div id="html_687d6fab4136466da326eef65a2a044a" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 PIYUNGAN</div>`)[0];
            popup_a0f35d8b30304b0ab964bf20d6ac9d6a.setContent(html_687d6fab4136466da326eef65a2a044a);
        

        marker_186e8c8be339456cba7144fb8f515383.bindPopup(popup_a0f35d8b30304b0ab964bf20d6ac9d6a)
        ;

        
    
    
            var marker_f93f0c273f014332b9002937b1698090 = L.marker(
                [-7.94033, 110.59708329999998],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_fdb91496155a41eda341ac6b133556d3 = L.popup({"maxWidth": "100%"});

        
            var html_6f14aaab458b4da8b977bb45864493be = $(`<div id="html_6f14aaab458b4da8b977bb45864493be" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 WONOSARI</div>`)[0];
            popup_fdb91496155a41eda341ac6b133556d3.setContent(html_6f14aaab458b4da8b977bb45864493be);
        

        marker_f93f0c273f014332b9002937b1698090.bindPopup(popup_fdb91496155a41eda341ac6b133556d3)
        ;

        
    
    
            var marker_df899a707f874e578fd3cf2ce0838327 = L.marker(
                [-7.928, 110.1462],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_184958bfa96a40b8a652e45342438b46 = L.popup({"maxWidth": "100%"});

        
            var html_43d75471054c4e7d8d350d2bc1e6e435 = $(`<div id="html_43d75471054c4e7d8d350d2bc1e6e435" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 PANJATAN</div>`)[0];
            popup_184958bfa96a40b8a652e45342438b46.setContent(html_43d75471054c4e7d8d350d2bc1e6e435);
        

        marker_df899a707f874e578fd3cf2ce0838327.bindPopup(popup_184958bfa96a40b8a652e45342438b46)
        ;

        
    
    
            var marker_7458a076ddef4af6b7f8b947938ab417 = L.marker(
                [-7.7722, 110.3329],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_12fd7a34a7a34714bb03a3047006010a = L.popup({"maxWidth": "100%"});

        
            var html_070d38d64f5e4961aac2153d9b9f3d4a = $(`<div id="html_070d38d64f5e4961aac2153d9b9f3d4a" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 GAMPING</div>`)[0];
            popup_12fd7a34a7a34714bb03a3047006010a.setContent(html_070d38d64f5e4961aac2153d9b9f3d4a);
        

        marker_7458a076ddef4af6b7f8b947938ab417.bindPopup(popup_12fd7a34a7a34714bb03a3047006010a)
        ;

        
    
    
            var marker_d6398d8e09f8415aa2343a26ac9d2811 = L.marker(
                [-7.9273, 110.7437],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_cb1e358412f544a39088c5c2543ce339 = L.popup({"maxWidth": "100%"});

        
            var html_e61a0700c2c64aa9a4778ef03d9192f4 = $(`<div id="html_e61a0700c2c64aa9a4778ef03d9192f4" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 PONJONG</div>`)[0];
            popup_cb1e358412f544a39088c5c2543ce339.setContent(html_e61a0700c2c64aa9a4778ef03d9192f4);
        

        marker_d6398d8e09f8415aa2343a26ac9d2811.bindPopup(popup_cb1e358412f544a39088c5c2543ce339)
        ;

        
    
    
            var marker_35fef35863d04bb6977456297b51164f = L.marker(
                [-7.8501845, 110.4784947],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_f9efb43f947840aa9fe14d06652a72ac = L.popup({"maxWidth": "100%"});

        
            var html_93d211520db548ceae76d957c1fced41 = $(`<div id="html_93d211520db548ceae76d957c1fced41" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 PATUK</div>`)[0];
            popup_f9efb43f947840aa9fe14d06652a72ac.setContent(html_93d211520db548ceae76d957c1fced41);
        

        marker_35fef35863d04bb6977456297b51164f.bindPopup(popup_f9efb43f947840aa9fe14d06652a72ac)
        ;

        
    
    
            var marker_4f3f26fe8b6246b984cc170180a8b6cb = L.marker(
                [-8.0123, 110.6247],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_60a70f9a2f044554b97405fddb995318 = L.popup({"maxWidth": "100%"});

        
            var html_9dc2618562904ce1b81202b18f34e8b6 = $(`<div id="html_9dc2618562904ce1b81202b18f34e8b6" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 SEMANU</div>`)[0];
            popup_60a70f9a2f044554b97405fddb995318.setContent(html_9dc2618562904ce1b81202b18f34e8b6);
        

        marker_4f3f26fe8b6246b984cc170180a8b6cb.bindPopup(popup_60a70f9a2f044554b97405fddb995318)
        ;

        
    
    
            var marker_49afd788357b47a2855070c2361dfdb5 = L.marker(
                [-7.8273, 110.2269],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_92467c4c77b446789ecd0f9ed0da755e = L.popup({"maxWidth": "100%"});

        
            var html_4fb9d6e44cf847fb8822bb24593b1d0e = $(`<div id="html_4fb9d6e44cf847fb8822bb24593b1d0e" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 SENTOLO</div>`)[0];
            popup_92467c4c77b446789ecd0f9ed0da755e.setContent(html_4fb9d6e44cf847fb8822bb24593b1d0e);
        

        marker_49afd788357b47a2855070c2361dfdb5.bindPopup(popup_92467c4c77b446789ecd0f9ed0da755e)
        ;

        
    
    
            var marker_edd7251dec234eef9286d0cb9297bd47 = L.marker(
                [-7.9764, 110.2836],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_1ed40e4c08d24065b001b03e4149d69d = L.popup({"maxWidth": "100%"});

        
            var html_01814bfa69054458b5cc481d086263f8 = $(`<div id="html_01814bfa69054458b5cc481d086263f8" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 SANDEN</div>`)[0];
            popup_1ed40e4c08d24065b001b03e4149d69d.setContent(html_01814bfa69054458b5cc481d086263f8);
        

        marker_edd7251dec234eef9286d0cb9297bd47.bindPopup(popup_1ed40e4c08d24065b001b03e4149d69d)
        ;

        
    
    
            var marker_b262df97789b402f843053237c6a1ad6 = L.marker(
                [-7.6759, 110.2626],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_2f2533f896ad446da6b4297639d111e8 = L.popup({"maxWidth": "100%"});

        
            var html_a80278eb747e440fa528cceaea549179 = $(`<div id="html_a80278eb747e440fa528cceaea549179" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 KALIBAWANG</div>`)[0];
            popup_2f2533f896ad446da6b4297639d111e8.setContent(html_a80278eb747e440fa528cceaea549179);
        

        marker_b262df97789b402f843053237c6a1ad6.bindPopup(popup_2f2533f896ad446da6b4297639d111e8)
        ;

        
    
    
            var marker_5a280039d9434b1e803679941cf39416 = L.marker(
                [-7.9135, 110.6879],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_5847950527874d80856457716801b698 = L.popup({"maxWidth": "100%"});

        
            var html_a39208e30cf245b0bf4c21cc9351046f = $(`<div id="html_a39208e30cf245b0bf4c21cc9351046f" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 KARANGMOJO</div>`)[0];
            popup_5847950527874d80856457716801b698.setContent(html_a39208e30cf245b0bf4c21cc9351046f);
        

        marker_5a280039d9434b1e803679941cf39416.bindPopup(popup_5847950527874d80856457716801b698)
        ;

        
    
    
            var marker_e9e3338c660442a693e356d01c1e67cf = L.marker(
                [-7.9359, 110.2498],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_f9c9a698113b4cd988ead81ba32a785e = L.popup({"maxWidth": "100%"});

        
            var html_853310cbb9214aca8927087e34907668 = $(`<div id="html_853310cbb9214aca8927087e34907668" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 SRANDAKAN</div>`)[0];
            popup_f9c9a698113b4cd988ead81ba32a785e.setContent(html_853310cbb9214aca8927087e34907668);
        

        marker_e9e3338c660442a693e356d01c1e67cf.bindPopup(popup_f9c9a698113b4cd988ead81ba32a785e)
        ;

        
    
    
            var marker_f5c67f82044a486ea4590bde3f9df1dd = L.marker(
                [-7.8049, 110.3024],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_0c97245d4cd34114b8d146f76a801776 = L.popup({"maxWidth": "100%"});

        
            var html_391140242fa2485aa49497bfebbbb8b2 = $(`<div id="html_391140242fa2485aa49497bfebbbb8b2" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 GAMPING</div>`)[0];
            popup_0c97245d4cd34114b8d146f76a801776.setContent(html_391140242fa2485aa49497bfebbbb8b2);
        

        marker_f5c67f82044a486ea4590bde3f9df1dd.bindPopup(popup_0c97245d4cd34114b8d146f76a801776)
        ;

        
    
    
            var marker_f18fb4c252ee42b293cd5d43a50287ba = L.marker(
                [-7.767, 110.4924],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_526cfd380e0d4bdebe7867f190dd2f82 = L.popup({"maxWidth": "100%"});

        
            var html_d1c9bfd5d8ef40fbaf9380573f24be57 = $(`<div id="html_d1c9bfd5d8ef40fbaf9380573f24be57" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 PRAMBANAN</div>`)[0];
            popup_526cfd380e0d4bdebe7867f190dd2f82.setContent(html_d1c9bfd5d8ef40fbaf9380573f24be57);
        

        marker_f18fb4c252ee42b293cd5d43a50287ba.bindPopup(popup_526cfd380e0d4bdebe7867f190dd2f82)
        ;

        
    
    
            var marker_53b5745de8214c58b1d926b9782b4c81 = L.marker(
                [-7.7915, 110.3509],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_cfaa328a4977440cb6a7d01454311530 = L.popup({"maxWidth": "100%"});

        
            var html_d0d7274d354c499ab0e3a2da7810b316 = $(`<div id="html_d0d7274d354c499ab0e3a2da7810b316" style="width: 100.0%; height: 100.0%;">SMP NEGERI 7 YOGYAKARTA</div>`)[0];
            popup_cfaa328a4977440cb6a7d01454311530.setContent(html_d0d7274d354c499ab0e3a2da7810b316);
        

        marker_53b5745de8214c58b1d926b9782b4c81.bindPopup(popup_cfaa328a4977440cb6a7d01454311530)
        ;

        
    
    
            var marker_885d185f83794350adbb1bbfd0390b14 = L.marker(
                [-7.8754, 110.0593],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_2377d6565a51465aba6abdc8f641acfa = L.popup({"maxWidth": "100%"});

        
            var html_89f6b3ff13b3408c82e5eb9b61ffd5ba = $(`<div id="html_89f6b3ff13b3408c82e5eb9b61ffd5ba" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 TEMON</div>`)[0];
            popup_2377d6565a51465aba6abdc8f641acfa.setContent(html_89f6b3ff13b3408c82e5eb9b61ffd5ba);
        

        marker_885d185f83794350adbb1bbfd0390b14.bindPopup(popup_2377d6565a51465aba6abdc8f641acfa)
        ;

        
    
    
            var marker_a182d0c419974cd29d4cbea8053281d8 = L.marker(
                [-7.7456, 110.1876],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_4cce88d766fb4ea1bfe296e809f4e2b2 = L.popup({"maxWidth": "100%"});

        
            var html_346ccad8bf5f4afab2e1db99e5aea60b = $(`<div id="html_346ccad8bf5f4afab2e1db99e5aea60b" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 GIRIMULYO</div>`)[0];
            popup_4cce88d766fb4ea1bfe296e809f4e2b2.setContent(html_346ccad8bf5f4afab2e1db99e5aea60b);
        

        marker_a182d0c419974cd29d4cbea8053281d8.bindPopup(popup_4cce88d766fb4ea1bfe296e809f4e2b2)
        ;

        
    
    
            var marker_13a7dc0968714d529afdc9494855b6dc = L.marker(
                [-7.9332, 110.43],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_86e36d30677f4b25b052174a4ab71292 = L.popup({"maxWidth": "100%"});

        
            var html_83fa816d77874739b2fde347873900a8 = $(`<div id="html_83fa816d77874739b2fde347873900a8" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 DLINGO</div>`)[0];
            popup_86e36d30677f4b25b052174a4ab71292.setContent(html_83fa816d77874739b2fde347873900a8);
        

        marker_13a7dc0968714d529afdc9494855b6dc.bindPopup(popup_86e36d30677f4b25b052174a4ab71292)
        ;

        
    
    
            var marker_f62b89225c2c4cc3854d07c5f69c1cbd = L.marker(
                [-7.649528299999999, 110.44375500000001],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_3fcacb3203e14b7a873b8a36e57f9675 = L.popup({"maxWidth": "100%"});

        
            var html_425d5b9e6ced46f885b8b369f4642221 = $(`<div id="html_425d5b9e6ced46f885b8b369f4642221" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 CANGKRINGAN</div>`)[0];
            popup_3fcacb3203e14b7a873b8a36e57f9675.setContent(html_425d5b9e6ced46f885b8b369f4642221);
        

        marker_f62b89225c2c4cc3854d07c5f69c1cbd.bindPopup(popup_3fcacb3203e14b7a873b8a36e57f9675)
        ;

        
    
    
            var marker_abf67acb87194dbdb3e34fd6196847b3 = L.marker(
                [-7.9519, 110.391],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_78ee5581c497451093d13054f8b70724 = L.popup({"maxWidth": "100%"});

        
            var html_652b460ec24a48bc81e12eea813b1cdf = $(`<div id="html_652b460ec24a48bc81e12eea813b1cdf" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 IMOGIRI</div>`)[0];
            popup_78ee5581c497451093d13054f8b70724.setContent(html_652b460ec24a48bc81e12eea813b1cdf);
        

        marker_abf67acb87194dbdb3e34fd6196847b3.bindPopup(popup_78ee5581c497451093d13054f8b70724)
        ;

        
    
    
            var marker_e27bf9b095b34eb5bc1fa722d63d5521 = L.marker(
                [-7.9266, 110.3506],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_c47dbbd7b41947ab8464cd32a7961fb5 = L.popup({"maxWidth": "100%"});

        
            var html_f22827f563f84736a30eb7aba2f056a7 = $(`<div id="html_f22827f563f84736a30eb7aba2f056a7" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 JETIS</div>`)[0];
            popup_c47dbbd7b41947ab8464cd32a7961fb5.setContent(html_f22827f563f84736a30eb7aba2f056a7);
        

        marker_e27bf9b095b34eb5bc1fa722d63d5521.bindPopup(popup_c47dbbd7b41947ab8464cd32a7961fb5)
        ;

        
    
    
            var marker_e2adca9c462f4385b9e40252dbdf05a3 = L.marker(
                [-7.7620000000000005, 110.346],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_a2318f8452bb40db977a10057b97bc53 = L.popup({"maxWidth": "100%"});

        
            var html_61e9a9367deb489fb7b1a5ca6d803da1 = $(`<div id="html_61e9a9367deb489fb7b1a5ca6d803da1" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 GAMPING</div>`)[0];
            popup_a2318f8452bb40db977a10057b97bc53.setContent(html_61e9a9367deb489fb7b1a5ca6d803da1);
        

        marker_e2adca9c462f4385b9e40252dbdf05a3.bindPopup(popup_a2318f8452bb40db977a10057b97bc53)
        ;

        
    
    
            var marker_f391fe0f6e4046949208705aa4e537aa = L.marker(
                [-7.8113, 110.1663],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_c232d52599794b858a33ddf294dbf7a1 = L.popup({"maxWidth": "100%"});

        
            var html_c4c0990f03c94ad0bfd7fd02ac807acd = $(`<div id="html_c4c0990f03c94ad0bfd7fd02ac807acd" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 PENGASIH</div>`)[0];
            popup_c232d52599794b858a33ddf294dbf7a1.setContent(html_c4c0990f03c94ad0bfd7fd02ac807acd);
        

        marker_f391fe0f6e4046949208705aa4e537aa.bindPopup(popup_c232d52599794b858a33ddf294dbf7a1)
        ;

        
    
    
            var marker_130036eda20c48c09a74c376dbb2f4ef = L.marker(
                [-7.9525317, 110.6757233],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_137212aae8ae49748f904e48d21aaa67 = L.popup({"maxWidth": "100%"});

        
            var html_a32faf08b85d446dbda80b014184a125 = $(`<div id="html_a32faf08b85d446dbda80b014184a125" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 KARANGMOJO</div>`)[0];
            popup_137212aae8ae49748f904e48d21aaa67.setContent(html_a32faf08b85d446dbda80b014184a125);
        

        marker_130036eda20c48c09a74c376dbb2f4ef.bindPopup(popup_137212aae8ae49748f904e48d21aaa67)
        ;

        
    
    
            var marker_4de6bc73844e47e8b85fcc0f7bbe212a = L.marker(
                [-7.8654, 110.741],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_caff0aa749b74a95984a3f1ca2594728 = L.popup({"maxWidth": "100%"});

        
            var html_9a8f044e91cb4a6c96c0ccea16678198 = $(`<div id="html_9a8f044e91cb4a6c96c0ccea16678198" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 SEMIN</div>`)[0];
            popup_caff0aa749b74a95984a3f1ca2594728.setContent(html_9a8f044e91cb4a6c96c0ccea16678198);
        

        marker_4de6bc73844e47e8b85fcc0f7bbe212a.bindPopup(popup_caff0aa749b74a95984a3f1ca2594728)
        ;

        
    
    
            var marker_6c529ec0fff5474b950ed5d978565102 = L.marker(
                [-8.0698, 110.5721],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_e63c7de5bca642cc8b6d803f99ca9173 = L.popup({"maxWidth": "100%"});

        
            var html_612d8013d7b244209d6cddefa942abff = $(`<div id="html_612d8013d7b244209d6cddefa942abff" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 TANJUNGSARI</div>`)[0];
            popup_e63c7de5bca642cc8b6d803f99ca9173.setContent(html_612d8013d7b244209d6cddefa942abff);
        

        marker_6c529ec0fff5474b950ed5d978565102.bindPopup(popup_e63c7de5bca642cc8b6d803f99ca9173)
        ;

        
    
    
            var marker_7b89149e7be54ee2a5004196e2c1a50b = L.marker(
                [-7.8084, 110.4054],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_c1611c63cc4240649ca34c7d25c77a00 = L.popup({"maxWidth": "100%"});

        
            var html_da76081fc6fa4b4ca4089d56e23bfb69 = $(`<div id="html_da76081fc6fa4b4ca4089d56e23bfb69" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 BANGUNTAPAN</div>`)[0];
            popup_c1611c63cc4240649ca34c7d25c77a00.setContent(html_da76081fc6fa4b4ca4089d56e23bfb69);
        

        marker_7b89149e7be54ee2a5004196e2c1a50b.bindPopup(popup_c1611c63cc4240649ca34c7d25c77a00)
        ;

        
    
    
            var marker_94c64b73949548a1b68322c9293863e1 = L.marker(
                [-7.8907417, 110.1126067],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_3c91c6d0c31e4d5bbc8d45a7440c2b58 = L.popup({"maxWidth": "100%"});

        
            var html_4c63846b2d5742eea4b598654a0efff9 = $(`<div id="html_4c63846b2d5742eea4b598654a0efff9" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 WATES</div>`)[0];
            popup_3c91c6d0c31e4d5bbc8d45a7440c2b58.setContent(html_4c63846b2d5742eea4b598654a0efff9);
        

        marker_94c64b73949548a1b68322c9293863e1.bindPopup(popup_3c91c6d0c31e4d5bbc8d45a7440c2b58)
        ;

        
    
    
            var marker_69cd4eed5dcd4593914bca43dd2c8c54 = L.marker(
                [-7.7839, 110.4822],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_341e5a901ba04629bf31a529b9549132 = L.popup({"maxWidth": "100%"});

        
            var html_e9c4e86ee674435e9ffe3f195959309c = $(`<div id="html_e9c4e86ee674435e9ffe3f195959309c" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 PRAMBANAN</div>`)[0];
            popup_341e5a901ba04629bf31a529b9549132.setContent(html_e9c4e86ee674435e9ffe3f195959309c);
        

        marker_69cd4eed5dcd4593914bca43dd2c8c54.bindPopup(popup_341e5a901ba04629bf31a529b9549132)
        ;

        
    
    
            var marker_76d78d2f3109450d921ae323efbdea79 = L.marker(
                [-7.8114, 110.3592],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_87fab0e58c2c4ca39495555b115b1236 = L.popup({"maxWidth": "100%"});

        
            var html_b0f9924cb1ca40098737c15b37e4e3c3 = $(`<div id="html_b0f9924cb1ca40098737c15b37e4e3c3" style="width: 100.0%; height: 100.0%;">SMP NEGERI 16 YOGYAKARTA</div>`)[0];
            popup_87fab0e58c2c4ca39495555b115b1236.setContent(html_b0f9924cb1ca40098737c15b37e4e3c3);
        

        marker_76d78d2f3109450d921ae323efbdea79.bindPopup(popup_87fab0e58c2c4ca39495555b115b1236)
        ;

        
    
    
            var marker_3aa0ce682ce941589f466e8caa9a7918 = L.marker(
                [-7.6858, 110.1839],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_914744cdaf18421eaa9aebe77c90f844 = L.popup({"maxWidth": "100%"});

        
            var html_89cf8fcfcf1743778ac32845ee24c8d3 = $(`<div id="html_89cf8fcfcf1743778ac32845ee24c8d3" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 SAMIGALUH</div>`)[0];
            popup_914744cdaf18421eaa9aebe77c90f844.setContent(html_89cf8fcfcf1743778ac32845ee24c8d3);
        

        marker_3aa0ce682ce941589f466e8caa9a7918.bindPopup(popup_914744cdaf18421eaa9aebe77c90f844)
        ;

        
    
    
            var marker_2a11129a22d84270b495c4240b0a868a = L.marker(
                [-7.6902266, 110.3427367],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_8b5f06abbd2643ecb24486b4ec1d418b = L.popup({"maxWidth": "100%"});

        
            var html_f0c618b5f9174dc6833b242c57cda50b = $(`<div id="html_f0c618b5f9174dc6833b242c57cda50b" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 SLEMAN</div>`)[0];
            popup_8b5f06abbd2643ecb24486b4ec1d418b.setContent(html_f0c618b5f9174dc6833b242c57cda50b);
        

        marker_2a11129a22d84270b495c4240b0a868a.bindPopup(popup_8b5f06abbd2643ecb24486b4ec1d418b)
        ;

        
    
    
            var marker_9c7d9f174b0a433980480257f658a192 = L.marker(
                [-7.8498, 110.323],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_30c126e0a79e4a6cb33b59934defa0c9 = L.popup({"maxWidth": "100%"});

        
            var html_a267756dabde4230aa48aaf877963b41 = $(`<div id="html_a267756dabde4230aa48aaf877963b41" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 SEWON</div>`)[0];
            popup_30c126e0a79e4a6cb33b59934defa0c9.setContent(html_a267756dabde4230aa48aaf877963b41);
        

        marker_9c7d9f174b0a433980480257f658a192.bindPopup(popup_30c126e0a79e4a6cb33b59934defa0c9)
        ;

        
    
    
            var marker_4e0ce5bbfa6e4c79a506390dba4c6731 = L.marker(
                [-8.0021817, 110.3451133],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_c6677e4d96a2476db753445152e0140f = L.popup({"maxWidth": "100%"});

        
            var html_00be6873e73a4cf1954fd5114b7bfb69 = $(`<div id="html_00be6873e73a4cf1954fd5114b7bfb69" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 PURWOSARI</div>`)[0];
            popup_c6677e4d96a2476db753445152e0140f.setContent(html_00be6873e73a4cf1954fd5114b7bfb69);
        

        marker_4e0ce5bbfa6e4c79a506390dba4c6731.bindPopup(popup_c6677e4d96a2476db753445152e0140f)
        ;

        
    
    
            var marker_41eb907b392049a9a1821b01b949ea83 = L.marker(
                [-7.9259, 110.3598],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_fcd7074e98ab49d5b302f96039e72cd3 = L.popup({"maxWidth": "100%"});

        
            var html_b43d1a5d85da4217b779d30034329fee = $(`<div id="html_b43d1a5d85da4217b779d30034329fee" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 JETIS</div>`)[0];
            popup_fcd7074e98ab49d5b302f96039e72cd3.setContent(html_b43d1a5d85da4217b779d30034329fee);
        

        marker_41eb907b392049a9a1821b01b949ea83.bindPopup(popup_fcd7074e98ab49d5b302f96039e72cd3)
        ;

        
    
    
            var marker_ebb3008d8b214a3a8b8139812dd2d892 = L.marker(
                [-8.1155, 110.7147],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_22e4363c9a8b4cc090c6c488e21e5392 = L.popup({"maxWidth": "100%"});

        
            var html_af77fd20a4f244e588a05fedcb74dad5 = $(`<div id="html_af77fd20a4f244e588a05fedcb74dad5" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 RONGKOP</div>`)[0];
            popup_22e4363c9a8b4cc090c6c488e21e5392.setContent(html_af77fd20a4f244e588a05fedcb74dad5);
        

        marker_ebb3008d8b214a3a8b8139812dd2d892.bindPopup(popup_22e4363c9a8b4cc090c6c488e21e5392)
        ;

        
    
    
            var marker_7fe046c1ee5f428e86e0ecf337db7479 = L.marker(
                [-7.65065, 110.3776783],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_604cbb19f4b14abba05ab8fdeaf3fff6 = L.popup({"maxWidth": "100%"});

        
            var html_c5a9e299aa814f2e82cc623716eea268 = $(`<div id="html_c5a9e299aa814f2e82cc623716eea268" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 TURI</div>`)[0];
            popup_604cbb19f4b14abba05ab8fdeaf3fff6.setContent(html_c5a9e299aa814f2e82cc623716eea268);
        

        marker_7fe046c1ee5f428e86e0ecf337db7479.bindPopup(popup_604cbb19f4b14abba05ab8fdeaf3fff6)
        ;

        
    
    
            var marker_b6df9685ee1c4eeea84c2e3d08f2b264 = L.marker(
                [-7.7160033, 110.35878829999999],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_84344f4f986c441ea3f865b3fefc5747 = L.popup({"maxWidth": "100%"});

        
            var html_d19c7df7e29c4c0ca20c03672909e740 = $(`<div id="html_d19c7df7e29c4c0ca20c03672909e740" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 SLEMAN</div>`)[0];
            popup_84344f4f986c441ea3f865b3fefc5747.setContent(html_d19c7df7e29c4c0ca20c03672909e740);
        

        marker_b6df9685ee1c4eeea84c2e3d08f2b264.bindPopup(popup_84344f4f986c441ea3f865b3fefc5747)
        ;

        
    
    
            var marker_8b07786b973a470b9ec62cb45a4239ea = L.marker(
                [-7.814, 110.4736],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_48e580cba7f244b5a082cb7a6599586f = L.popup({"maxWidth": "100%"});

        
            var html_779ee7c47a8c45ebbdc5fe2695e44e45 = $(`<div id="html_779ee7c47a8c45ebbdc5fe2695e44e45" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 BERBAH</div>`)[0];
            popup_48e580cba7f244b5a082cb7a6599586f.setContent(html_779ee7c47a8c45ebbdc5fe2695e44e45);
        

        marker_8b07786b973a470b9ec62cb45a4239ea.bindPopup(popup_48e580cba7f244b5a082cb7a6599586f)
        ;

        
    
    
            var marker_7850aef2debd4ef3a689057b280080bb = L.marker(
                [-7.9768, 110.708],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_85162ef443874256af1f7b8a3fbbd702 = L.popup({"maxWidth": "100%"});

        
            var html_f811a93625be4fa38e5479a189fdcd40 = $(`<div id="html_f811a93625be4fa38e5479a189fdcd40" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 PONJONG</div>`)[0];
            popup_85162ef443874256af1f7b8a3fbbd702.setContent(html_f811a93625be4fa38e5479a189fdcd40);
        

        marker_7850aef2debd4ef3a689057b280080bb.bindPopup(popup_85162ef443874256af1f7b8a3fbbd702)
        ;

        
    
    
            var marker_a45f77fdd48f4a369a6a3e9b5a02c508 = L.marker(
                [-7.7891, 110.1607],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_ef373eed09ff420b87b2fc146fc358b1 = L.popup({"maxWidth": "100%"});

        
            var html_65a577e9f8e94fb89ed62d10b18bbf6f = $(`<div id="html_65a577e9f8e94fb89ed62d10b18bbf6f" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 PENGASIH</div>`)[0];
            popup_ef373eed09ff420b87b2fc146fc358b1.setContent(html_65a577e9f8e94fb89ed62d10b18bbf6f);
        

        marker_a45f77fdd48f4a369a6a3e9b5a02c508.bindPopup(popup_ef373eed09ff420b87b2fc146fc358b1)
        ;

        
    
    
            var marker_5226955f5f414379b7611a010cce71e6 = L.marker(
                [-7.8397, 110.3129],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_572abfdef8504900a1fa538111a6e78e = L.popup({"maxWidth": "100%"});

        
            var html_c9f4b56fce944b7eac51c200ed164d3f = $(`<div id="html_c9f4b56fce944b7eac51c200ed164d3f" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 KASIHAN</div>`)[0];
            popup_572abfdef8504900a1fa538111a6e78e.setContent(html_c9f4b56fce944b7eac51c200ed164d3f);
        

        marker_5226955f5f414379b7611a010cce71e6.bindPopup(popup_572abfdef8504900a1fa538111a6e78e)
        ;

        
    
    
            var marker_a563ec62ade54c64a674972a30b9ec63 = L.marker(
                [-7.7526, 110.3645],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_20e1cae3972a4452ad2aeb67d3fd032e = L.popup({"maxWidth": "100%"});

        
            var html_beec6441e5b6477a85f3ae1194f23e11 = $(`<div id="html_beec6441e5b6477a85f3ae1194f23e11" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 MLATI</div>`)[0];
            popup_20e1cae3972a4452ad2aeb67d3fd032e.setContent(html_beec6441e5b6477a85f3ae1194f23e11);
        

        marker_a563ec62ade54c64a674972a30b9ec63.bindPopup(popup_20e1cae3972a4452ad2aeb67d3fd032e)
        ;

        
    
    
            var marker_1ad6a456b8944ac3875d0678476a6d6e = L.marker(
                [-8.1005, 110.691],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_b4741f52483f4a839d22beaf51892038 = L.popup({"maxWidth": "100%"});

        
            var html_f165781f9aa44ea4b2c0fd5a57a2b544 = $(`<div id="html_f165781f9aa44ea4b2c0fd5a57a2b544" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 TEPUS</div>`)[0];
            popup_b4741f52483f4a839d22beaf51892038.setContent(html_f165781f9aa44ea4b2c0fd5a57a2b544);
        

        marker_1ad6a456b8944ac3875d0678476a6d6e.bindPopup(popup_b4741f52483f4a839d22beaf51892038)
        ;

        
    
    
            var marker_ef9477b5849c4c94853903d76f82f531 = L.marker(
                [-7.6963666, 110.3728733],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_6002e1c1f8214552a2f89e5094f1dfd3 = L.popup({"maxWidth": "100%"});

        
            var html_d85f88ebbd264ab8b89d95acfccff3c0 = $(`<div id="html_d85f88ebbd264ab8b89d95acfccff3c0" style="width: 100.0%; height: 100.0%;">SMP NEGERI 5 SLEMAN</div>`)[0];
            popup_6002e1c1f8214552a2f89e5094f1dfd3.setContent(html_d85f88ebbd264ab8b89d95acfccff3c0);
        

        marker_ef9477b5849c4c94853903d76f82f531.bindPopup(popup_6002e1c1f8214552a2f89e5094f1dfd3)
        ;

        
    
    
            var marker_d84160b475944964883127ae6e47814b = L.marker(
                [-7.658931699999999, 110.3277367],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_17131879455f43d9bdc48a1a7c1108c0 = L.popup({"maxWidth": "100%"});

        
            var html_088b9e8c5281408088b6b126efc58ed0 = $(`<div id="html_088b9e8c5281408088b6b126efc58ed0" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 TEMPEL</div>`)[0];
            popup_17131879455f43d9bdc48a1a7c1108c0.setContent(html_088b9e8c5281408088b6b126efc58ed0);
        

        marker_d84160b475944964883127ae6e47814b.bindPopup(popup_17131879455f43d9bdc48a1a7c1108c0)
        ;

        
    
    
            var marker_1be0575bbb0a4f5db9972bd6fb146f29 = L.marker(
                [-7.7785, 110.25200000000001],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_5f94c3e5d9c94a278e6b948944aa9ce4 = L.popup({"maxWidth": "100%"});

        
            var html_745a410594f24455bf2dc7f4ece60ac1 = $(`<div id="html_745a410594f24455bf2dc7f4ece60ac1" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 MOYUDAN</div>`)[0];
            popup_5f94c3e5d9c94a278e6b948944aa9ce4.setContent(html_745a410594f24455bf2dc7f4ece60ac1);
        

        marker_1be0575bbb0a4f5db9972bd6fb146f29.bindPopup(popup_5f94c3e5d9c94a278e6b948944aa9ce4)
        ;

        
    
    
            var marker_a0b268cba7e346f79f4dcf6c72200a7e = L.marker(
                [-7.8134, 110.3116],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_0e335c4385684c11a2814601ba93934b = L.popup({"maxWidth": "100%"});

        
            var html_6d611f01ddbb49a8ab347af18a93bd6a = $(`<div id="html_6d611f01ddbb49a8ab347af18a93bd6a" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 GAMPING</div>`)[0];
            popup_0e335c4385684c11a2814601ba93934b.setContent(html_6d611f01ddbb49a8ab347af18a93bd6a);
        

        marker_a0b268cba7e346f79f4dcf6c72200a7e.bindPopup(popup_0e335c4385684c11a2814601ba93934b)
        ;

        
    
    
            var marker_5c1e9c34256f41a29926da9f18788a8c = L.marker(
                [-7.920221700000001, 110.5352763],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_5066f96d44004ca58caa329540235c94 = L.popup({"maxWidth": "100%"});

        
            var html_dcadf1de786749edb2f708f3020decbb = $(`<div id="html_dcadf1de786749edb2f708f3020decbb" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 PLAYEN</div>`)[0];
            popup_5066f96d44004ca58caa329540235c94.setContent(html_dcadf1de786749edb2f708f3020decbb);
        

        marker_5c1e9c34256f41a29926da9f18788a8c.bindPopup(popup_5066f96d44004ca58caa329540235c94)
        ;

        
    
    
            var marker_d451c86d424a41a3a5cc39fed0c6ac3e = L.marker(
                [-8.0877, 110.6261],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_45b94e8f25544c6da43304e6b3ba7d67 = L.popup({"maxWidth": "100%"});

        
            var html_47c8b8e06f534d44909f365219f3ebd5 = $(`<div id="html_47c8b8e06f534d44909f365219f3ebd5" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 TEPUS</div>`)[0];
            popup_45b94e8f25544c6da43304e6b3ba7d67.setContent(html_47c8b8e06f534d44909f365219f3ebd5);
        

        marker_d451c86d424a41a3a5cc39fed0c6ac3e.bindPopup(popup_45b94e8f25544c6da43304e6b3ba7d67)
        ;

        
    
    
            var marker_9c421ede3307459e989178e432c00c3a = L.marker(
                [-7.8953, 110.2682],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_8473c789e872402a8ab69d8358215d41 = L.popup({"maxWidth": "100%"});

        
            var html_f6fd0159c4664eb5bcb0a01e4836300c = $(`<div id="html_f6fd0159c4664eb5bcb0a01e4836300c" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 LENDAH</div>`)[0];
            popup_8473c789e872402a8ab69d8358215d41.setContent(html_f6fd0159c4664eb5bcb0a01e4836300c);
        

        marker_9c421ede3307459e989178e432c00c3a.bindPopup(popup_8473c789e872402a8ab69d8358215d41)
        ;

        
    
    
            var marker_45ad6f00df5e479a840c2be62977ff2e = L.marker(
                [-7.763999999999999, 110.3151],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_97de3166387444b5b8d2b39292bc89b7 = L.popup({"maxWidth": "100%"});

        
            var html_5da4e78e3c16416cb8ffbe0b5c54824e = $(`<div id="html_5da4e78e3c16416cb8ffbe0b5c54824e" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 GODEAN</div>`)[0];
            popup_97de3166387444b5b8d2b39292bc89b7.setContent(html_5da4e78e3c16416cb8ffbe0b5c54824e);
        

        marker_45ad6f00df5e479a840c2be62977ff2e.bindPopup(popup_97de3166387444b5b8d2b39292bc89b7)
        ;

        
    
    
            var marker_7ab8d9d2c7924fd4b2499b50dd1a0d20 = L.marker(
                [-7.7785, 110.3672],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_139404a31d204f44bfd264e0c4ad833f = L.popup({"maxWidth": "100%"});

        
            var html_132a6b152679495d92a421900ca59b73 = $(`<div id="html_132a6b152679495d92a421900ca59b73" style="width: 100.0%; height: 100.0%;">SMP NEGERI 6 YOGYAKARTA</div>`)[0];
            popup_139404a31d204f44bfd264e0c4ad833f.setContent(html_132a6b152679495d92a421900ca59b73);
        

        marker_7ab8d9d2c7924fd4b2499b50dd1a0d20.bindPopup(popup_139404a31d204f44bfd264e0c4ad833f)
        ;

        
    
    
            var marker_9bf75ae4857a4f8382c4df6384653419 = L.marker(
                [-8.0683667, 110.5506033],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_0bbee9521cc042b38b85951d7d8d68c4 = L.popup({"maxWidth": "100%"});

        
            var html_fb49d86d96ba46579c2821c3693fd4cc = $(`<div id="html_fb49d86d96ba46579c2821c3693fd4cc" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 PALIYAN</div>`)[0];
            popup_0bbee9521cc042b38b85951d7d8d68c4.setContent(html_fb49d86d96ba46579c2821c3693fd4cc);
        

        marker_9bf75ae4857a4f8382c4df6384653419.bindPopup(popup_0bbee9521cc042b38b85951d7d8d68c4)
        ;

        
    
    
            var marker_68dafb7b278c4b3599a36de3c1c21009 = L.marker(
                [-7.7244, 110.4699],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_8a51fabc26a4487c8fa5f561bbe7efab = L.popup({"maxWidth": "100%"});

        
            var html_fa29fa8e0ed14568ad50f3329b1bea01 = $(`<div id="html_fa29fa8e0ed14568ad50f3329b1bea01" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 KALASAN</div>`)[0];
            popup_8a51fabc26a4487c8fa5f561bbe7efab.setContent(html_fa29fa8e0ed14568ad50f3329b1bea01);
        

        marker_68dafb7b278c4b3599a36de3c1c21009.bindPopup(popup_8a51fabc26a4487c8fa5f561bbe7efab)
        ;

        
    
    
            var marker_9af7fc19d71f402dae70dcbe54721f53 = L.marker(
                [-7.8673494999999996, 110.5597608],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_4b41df4b2ed14fd092900ef41a6af890 = L.popup({"maxWidth": "100%"});

        
            var html_d8b2c839904143348b09d12bedb7f727 = $(`<div id="html_d8b2c839904143348b09d12bedb7f727" style="width: 100.0%; height: 100.0%;">SMP NEGERI 5 PATUK</div>`)[0];
            popup_4b41df4b2ed14fd092900ef41a6af890.setContent(html_d8b2c839904143348b09d12bedb7f727);
        

        marker_9af7fc19d71f402dae70dcbe54721f53.bindPopup(popup_4b41df4b2ed14fd092900ef41a6af890)
        ;

        
    
    
            var marker_872d755c3a7b49fbb9375f2dc38368c1 = L.marker(
                [-7.6695766, 110.41795829999998],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_919e56a40bb148118c84888ea15e8dd7 = L.popup({"maxWidth": "100%"});

        
            var html_8a3cede39c584cc5b28ea66a90050ca9 = $(`<div id="html_8a3cede39c584cc5b28ea66a90050ca9" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 PAKEM</div>`)[0];
            popup_919e56a40bb148118c84888ea15e8dd7.setContent(html_8a3cede39c584cc5b28ea66a90050ca9);
        

        marker_872d755c3a7b49fbb9375f2dc38368c1.bindPopup(popup_919e56a40bb148118c84888ea15e8dd7)
        ;

        
    
    
            var marker_d7a22697991d4c8e93c0cfc039366901 = L.marker(
                [-8.0942, 110.5309],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_98144d3241cd4940aa343ede61292416 = L.popup({"maxWidth": "100%"});

        
            var html_9d64778af0644085b558c608327f6aff = $(`<div id="html_9d64778af0644085b558c608327f6aff" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 SAPTOSARI</div>`)[0];
            popup_98144d3241cd4940aa343ede61292416.setContent(html_9d64778af0644085b558c608327f6aff);
        

        marker_d7a22697991d4c8e93c0cfc039366901.bindPopup(popup_98144d3241cd4940aa343ede61292416)
        ;

        
    
    
            var marker_54d7880daa8249409b3d6660f3340573 = L.marker(
                [-7.8412, 110.7056],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_500e87f25e5a4b6e9bc26730f04609f4 = L.popup({"maxWidth": "100%"});

        
            var html_e28cfa8901cc481092f8b20f9d9d561e = $(`<div id="html_e28cfa8901cc481092f8b20f9d9d561e" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 NGAWEN</div>`)[0];
            popup_500e87f25e5a4b6e9bc26730f04609f4.setContent(html_e28cfa8901cc481092f8b20f9d9d561e);
        

        marker_54d7880daa8249409b3d6660f3340573.bindPopup(popup_500e87f25e5a4b6e9bc26730f04609f4)
        ;

        
    
    
            var marker_dd49b147a83c41eca9470ce6fb3a2029 = L.marker(
                [-7.6391516, 110.4258866],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_8e3eb8f190d24c25ac64acec22e7be39 = L.popup({"maxWidth": "100%"});

        
            var html_f821080ed6e14ad7bfea5badf31fe50e = $(`<div id="html_f821080ed6e14ad7bfea5badf31fe50e" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 PAKEM</div>`)[0];
            popup_8e3eb8f190d24c25ac64acec22e7be39.setContent(html_f821080ed6e14ad7bfea5badf31fe50e);
        

        marker_dd49b147a83c41eca9470ce6fb3a2029.bindPopup(popup_8e3eb8f190d24c25ac64acec22e7be39)
        ;

        
    
    
            var marker_48e575be31744cf58a0cdfa9667b0bf8 = L.marker(
                [-8.0469, 110.5134],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_6fe9a93f43654f15ab81ae850832db16 = L.popup({"maxWidth": "100%"});

        
            var html_a8ed5ca0f52344baac8d5ef70dec594c = $(`<div id="html_a8ed5ca0f52344baac8d5ef70dec594c" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 SAPTOSARI</div>`)[0];
            popup_6fe9a93f43654f15ab81ae850832db16.setContent(html_a8ed5ca0f52344baac8d5ef70dec594c);
        

        marker_48e575be31744cf58a0cdfa9667b0bf8.bindPopup(popup_6fe9a93f43654f15ab81ae850832db16)
        ;

        
    
    
            var marker_d88a04da11c742cb86dce1b99e746cb6 = L.marker(
                [-7.8319, 110.7614],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_55bc4d6e8f6a4611891d5f81fc511bd7 = L.popup({"maxWidth": "100%"});

        
            var html_6174a38132ab439a800c8498e3b6b33a = $(`<div id="html_6174a38132ab439a800c8498e3b6b33a" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 SEMIN</div>`)[0];
            popup_55bc4d6e8f6a4611891d5f81fc511bd7.setContent(html_6174a38132ab439a800c8498e3b6b33a);
        

        marker_d88a04da11c742cb86dce1b99e746cb6.bindPopup(popup_55bc4d6e8f6a4611891d5f81fc511bd7)
        ;

        
    
    
            var marker_2138454df8ef4b4998b565f0c76b6e5a = L.marker(
                [-7.8418, 110.09899999999999],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_1033019c71744a7e926590e817e4f769 = L.popup({"maxWidth": "100%"});

        
            var html_ce7d250e3aee4909a58dc6493a204e42 = $(`<div id="html_ce7d250e3aee4909a58dc6493a204e42" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 KOKAP</div>`)[0];
            popup_1033019c71744a7e926590e817e4f769.setContent(html_ce7d250e3aee4909a58dc6493a204e42);
        

        marker_2138454df8ef4b4998b565f0c76b6e5a.bindPopup(popup_1033019c71744a7e926590e817e4f769)
        ;

        
    
    
            var marker_619b9b22c6ac4a6d866b940bb9fc08f5 = L.marker(
                [-7.8273, 110.1991],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_a386aae064a348b6a46d633d9da3e155 = L.popup({"maxWidth": "100%"});

        
            var html_7b77bb1c9f2d451bb2924da48e313b67 = $(`<div id="html_7b77bb1c9f2d451bb2924da48e313b67" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 SENTOLO</div>`)[0];
            popup_a386aae064a348b6a46d633d9da3e155.setContent(html_7b77bb1c9f2d451bb2924da48e313b67);
        

        marker_619b9b22c6ac4a6d866b940bb9fc08f5.bindPopup(popup_a386aae064a348b6a46d633d9da3e155)
        ;

        
    
    
            var marker_9c6f1b1da4c54869a2fbee2d9fa3ca94 = L.marker(
                [-7.8434, 110.5913],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_ca2d963a0eda4ab3ab23d1b0a0fe6b59 = L.popup({"maxWidth": "100%"});

        
            var html_a1f67664b30a4ea78e4f0f3be60ca582 = $(`<div id="html_a1f67664b30a4ea78e4f0f3be60ca582" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 GEDANGSARI</div>`)[0];
            popup_ca2d963a0eda4ab3ab23d1b0a0fe6b59.setContent(html_a1f67664b30a4ea78e4f0f3be60ca582);
        

        marker_9c6f1b1da4c54869a2fbee2d9fa3ca94.bindPopup(popup_ca2d963a0eda4ab3ab23d1b0a0fe6b59)
        ;

        
    
    
            var marker_ba04d6b5508545da8d8eb88127081cef = L.marker(
                [-7.9114, 110.4691],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_09da5fa3e35d4e0a8da125712a17b2e0 = L.popup({"maxWidth": "100%"});

        
            var html_26ce0df2654a452db9df077d7822c698 = $(`<div id="html_26ce0df2654a452db9df077d7822c698" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 DLINGO</div>`)[0];
            popup_09da5fa3e35d4e0a8da125712a17b2e0.setContent(html_26ce0df2654a452db9df077d7822c698);
        

        marker_ba04d6b5508545da8d8eb88127081cef.bindPopup(popup_09da5fa3e35d4e0a8da125712a17b2e0)
        ;

        
    
    
            var marker_f3ba8457afbe4b75880fdab4a82183ba = L.marker(
                [-7.7836, 110.5068],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_6ad19cd0e6be4036a2569d3f9b9c4f98 = L.popup({"maxWidth": "100%"});

        
            var html_81af987eca754c3f97f53ef93c2cdc74 = $(`<div id="html_81af987eca754c3f97f53ef93c2cdc74" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 PRAMBANAN</div>`)[0];
            popup_6ad19cd0e6be4036a2569d3f9b9c4f98.setContent(html_81af987eca754c3f97f53ef93c2cdc74);
        

        marker_f3ba8457afbe4b75880fdab4a82183ba.bindPopup(popup_6ad19cd0e6be4036a2569d3f9b9c4f98)
        ;

        
    
    
            var marker_65abf4df57c343679a7cf779fba91cb4 = L.marker(
                [-8.0016, 110.6485],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_d02d0bd996654da5b1cd554b629a1790 = L.popup({"maxWidth": "100%"});

        
            var html_27406d8337344e3f8a790f2b8905c32e = $(`<div id="html_27406d8337344e3f8a790f2b8905c32e" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 SEMANU</div>`)[0];
            popup_d02d0bd996654da5b1cd554b629a1790.setContent(html_27406d8337344e3f8a790f2b8905c32e);
        

        marker_65abf4df57c343679a7cf779fba91cb4.bindPopup(popup_d02d0bd996654da5b1cd554b629a1790)
        ;

        
    
    
            var marker_d4175423cf974b63bfebe69c502dfd1f = L.marker(
                [-7.8866, 110.2736],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_7657101657c8489482b41634eb74ce50 = L.popup({"maxWidth": "100%"});

        
            var html_55f9bd0405b64018aa6b6ee4b9cf15bb = $(`<div id="html_55f9bd0405b64018aa6b6ee4b9cf15bb" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 PAJANGAN</div>`)[0];
            popup_7657101657c8489482b41634eb74ce50.setContent(html_55f9bd0405b64018aa6b6ee4b9cf15bb);
        

        marker_d4175423cf974b63bfebe69c502dfd1f.bindPopup(popup_7657101657c8489482b41634eb74ce50)
        ;

        
    
    
            var marker_733739eac69b4416bc6c37c8f0ab73fc = L.marker(
                [-7.8644, 110.2463],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_b2c4b787524a4e85bd99c1dddfe4fdef = L.popup({"maxWidth": "100%"});

        
            var html_ac79653ebf604de387a64f669a817d62 = $(`<div id="html_ac79653ebf604de387a64f669a817d62" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 SENTOLO</div>`)[0];
            popup_b2c4b787524a4e85bd99c1dddfe4fdef.setContent(html_ac79653ebf604de387a64f669a817d62);
        

        marker_733739eac69b4416bc6c37c8f0ab73fc.bindPopup(popup_b2c4b787524a4e85bd99c1dddfe4fdef)
        ;

        
    
    
            var marker_450f6b1d3b4840388df517b546ed0950 = L.marker(
                [-7.8707617, 110.14095],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_49ac42be7d5f4dba80af90324143e5fd = L.popup({"maxWidth": "100%"});

        
            var html_49fe5bfe564143839146f195e1e7256f = $(`<div id="html_49fe5bfe564143839146f195e1e7256f" style="width: 100.0%; height: 100.0%;">SMP NEGERI 5 WATES</div>`)[0];
            popup_49ac42be7d5f4dba80af90324143e5fd.setContent(html_49fe5bfe564143839146f195e1e7256f);
        

        marker_450f6b1d3b4840388df517b546ed0950.bindPopup(popup_49ac42be7d5f4dba80af90324143e5fd)
        ;

        
    
    
            var marker_a9c2e5eba39e40269429c8c41d7276a2 = L.marker(
                [-7.6537467, 110.35640829999998],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_4cfeb234c3b34e3f92863feccc4c1c23 = L.popup({"maxWidth": "100%"});

        
            var html_52f824ee0c034e0e89304058f610e98d = $(`<div id="html_52f824ee0c034e0e89304058f610e98d" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 TURI</div>`)[0];
            popup_4cfeb234c3b34e3f92863feccc4c1c23.setContent(html_52f824ee0c034e0e89304058f610e98d);
        

        marker_a9c2e5eba39e40269429c8c41d7276a2.bindPopup(popup_4cfeb234c3b34e3f92863feccc4c1c23)
        ;

        
    
    
            var marker_ab896e4ff2464357aa959774b668f3d6 = L.marker(
                [-7.8839999999999995, 110.7439],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_9880813e61db4ed0bfb9cfc811717909 = L.popup({"maxWidth": "100%"});

        
            var html_e7e6f037a2f848e2b3f0f34c99e014c2 = $(`<div id="html_e7e6f037a2f848e2b3f0f34c99e014c2" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 SEMIN</div>`)[0];
            popup_9880813e61db4ed0bfb9cfc811717909.setContent(html_e7e6f037a2f848e2b3f0f34c99e014c2);
        

        marker_ab896e4ff2464357aa959774b668f3d6.bindPopup(popup_9880813e61db4ed0bfb9cfc811717909)
        ;

        
    
    
            var marker_3cb4feb08b9348b1ab19e0f923d51dce = L.marker(
                [-7.8203, 110.6906],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_3fa2b5ac7f8e454b9efa356c7ef09aad = L.popup({"maxWidth": "100%"});

        
            var html_2f19522f7f2f452a8f97fa3e490587d0 = $(`<div id="html_2f19522f7f2f452a8f97fa3e490587d0" style="width: 100.0%; height: 100.0%;">SMP NEGERI 5 NGAWEN</div>`)[0];
            popup_3fa2b5ac7f8e454b9efa356c7ef09aad.setContent(html_2f19522f7f2f452a8f97fa3e490587d0);
        

        marker_3cb4feb08b9348b1ab19e0f923d51dce.bindPopup(popup_3fa2b5ac7f8e454b9efa356c7ef09aad)
        ;

        
    
    
            var marker_760b6d639b3640309310c1049af11d1a = L.marker(
                [-7.8949433, 110.1466067],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_ec727dde40bb4fba9e4ac865b865571b = L.popup({"maxWidth": "100%"});

        
            var html_48b69c4a1fcc463a95204182585af5b1 = $(`<div id="html_48b69c4a1fcc463a95204182585af5b1" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 WATES</div>`)[0];
            popup_ec727dde40bb4fba9e4ac865b865571b.setContent(html_48b69c4a1fcc463a95204182585af5b1);
        

        marker_760b6d639b3640309310c1049af11d1a.bindPopup(popup_ec727dde40bb4fba9e4ac865b865571b)
        ;

        
    
    
            var marker_18d972fb0fc24c7bbca7c86c720484df = L.marker(
                [-7.9388, 110.2752],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_31293cfa6aaa4c649f8733cecaf44fa0 = L.popup({"maxWidth": "100%"});

        
            var html_70c306c32e104376ba10d6f60e5dc27a = $(`<div id="html_70c306c32e104376ba10d6f60e5dc27a" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 PANDAK</div>`)[0];
            popup_31293cfa6aaa4c649f8733cecaf44fa0.setContent(html_70c306c32e104376ba10d6f60e5dc27a);
        

        marker_18d972fb0fc24c7bbca7c86c720484df.bindPopup(popup_31293cfa6aaa4c649f8733cecaf44fa0)
        ;

        
    
    
            var marker_c3eda429d31c4404907ca92d98ace0c1 = L.marker(
                [-8.0634, 110.4316],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_a0260bcd76894fb980e387861e611583 = L.popup({"maxWidth": "100%"});

        
            var html_2ede0334afc64f78840f5dcad55098a0 = $(`<div id="html_2ede0334afc64f78840f5dcad55098a0" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 PANGGANG</div>`)[0];
            popup_a0260bcd76894fb980e387861e611583.setContent(html_2ede0334afc64f78840f5dcad55098a0);
        

        marker_c3eda429d31c4404907ca92d98ace0c1.bindPopup(popup_a0260bcd76894fb980e387861e611583)
        ;

        
    
    
            var marker_59a3e90af18e441f9f886906a295257c = L.marker(
                [-7.8035, 110.2739],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_4d87abbe67304e1eb09bcefab232cb52 = L.popup({"maxWidth": "100%"});

        
            var html_4a8977f4c9594ff4a74c565be1c42662 = $(`<div id="html_4a8977f4c9594ff4a74c565be1c42662" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 SEDAYU</div>`)[0];
            popup_4d87abbe67304e1eb09bcefab232cb52.setContent(html_4a8977f4c9594ff4a74c565be1c42662);
        

        marker_59a3e90af18e441f9f886906a295257c.bindPopup(popup_4d87abbe67304e1eb09bcefab232cb52)
        ;

        
    
    
            var marker_eeaafb9d4c3e4dfd9fefcac46fdefbaa = L.marker(
                [-7.7553, 110.40799999999999],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_97d4990f9e2d4aeba73a115896a97407 = L.popup({"maxWidth": "100%"});

        
            var html_15334d3f4bab4c03aaa3db505a9e8bc5 = $(`<div id="html_15334d3f4bab4c03aaa3db505a9e8bc5" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 DEPOK</div>`)[0];
            popup_97d4990f9e2d4aeba73a115896a97407.setContent(html_15334d3f4bab4c03aaa3db505a9e8bc5);
        

        marker_eeaafb9d4c3e4dfd9fefcac46fdefbaa.bindPopup(popup_97d4990f9e2d4aeba73a115896a97407)
        ;

        
    
    
            var marker_fdc14954914c47b5afcce7d49c921ea0 = L.marker(
                [-7.871894999999999, 110.5198567],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_06a502e9d4fa47469a4569610e1a3cba = L.popup({"maxWidth": "100%"});

        
            var html_ae8926ab8fc34dd9b7ea32b276e7d2bf = $(`<div id="html_ae8926ab8fc34dd9b7ea32b276e7d2bf" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 PATUK</div>`)[0];
            popup_06a502e9d4fa47469a4569610e1a3cba.setContent(html_ae8926ab8fc34dd9b7ea32b276e7d2bf);
        

        marker_fdc14954914c47b5afcce7d49c921ea0.bindPopup(popup_06a502e9d4fa47469a4569610e1a3cba)
        ;

        
    
    
            var marker_acdafa7001fd469aa14ba42028554e39 = L.marker(
                [-7.8475, 110.3587],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_13b8892f48ea47ff9b9a0752d4597106 = L.popup({"maxWidth": "100%"});

        
            var html_3af2eb2867b6435b9dd3c038a9e2645e = $(`<div id="html_3af2eb2867b6435b9dd3c038a9e2645e" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 SEWON</div>`)[0];
            popup_13b8892f48ea47ff9b9a0752d4597106.setContent(html_3af2eb2867b6435b9dd3c038a9e2645e);
        

        marker_acdafa7001fd469aa14ba42028554e39.bindPopup(popup_13b8892f48ea47ff9b9a0752d4597106)
        ;

        
    
    
            var marker_8d342f70a9dc4459a33b5fc3e25b8f0f = L.marker(
                [-7.7612, 110.4281],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_444e7729f74b4c8aa3d32921c0940f81 = L.popup({"maxWidth": "100%"});

        
            var html_af3acbd6940b4670beff284652674a05 = $(`<div id="html_af3acbd6940b4670beff284652674a05" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 DEPOK</div>`)[0];
            popup_444e7729f74b4c8aa3d32921c0940f81.setContent(html_af3acbd6940b4670beff284652674a05);
        

        marker_8d342f70a9dc4459a33b5fc3e25b8f0f.bindPopup(popup_444e7729f74b4c8aa3d32921c0940f81)
        ;

        
    
    
            var marker_6855399db4284f42a9edf362a2da59f6 = L.marker(
                [-7.6887, 110.2568],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_8a22604d267542718d1836b6d94217fe = L.popup({"maxWidth": "100%"});

        
            var html_abb65e412f3b4452914eefdc36872ace = $(`<div id="html_abb65e412f3b4452914eefdc36872ace" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 KALIBAWANG</div>`)[0];
            popup_8a22604d267542718d1836b6d94217fe.setContent(html_abb65e412f3b4452914eefdc36872ace);
        

        marker_6855399db4284f42a9edf362a2da59f6.bindPopup(popup_8a22604d267542718d1836b6d94217fe)
        ;

        
    
    
            var marker_aa0141495aee41319bcc3da1f5b49a07 = L.marker(
                [-7.7904, 110.4592],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_6fd12533e65f4ed68fee86b6aea8303c = L.popup({"maxWidth": "100%"});

        
            var html_a270fee2793c48cc8a3310aecacadc24 = $(`<div id="html_a270fee2793c48cc8a3310aecacadc24" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 BERBAH</div>`)[0];
            popup_6fd12533e65f4ed68fee86b6aea8303c.setContent(html_a270fee2793c48cc8a3310aecacadc24);
        

        marker_aa0141495aee41319bcc3da1f5b49a07.bindPopup(popup_6fd12533e65f4ed68fee86b6aea8303c)
        ;

        
    
    
            var marker_9c4f6b4ee1cf42e09fd9ca1604d57718 = L.marker(
                [-7.885731699999999, 110.5991883],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_29443c7d3c1d4d70bb9d594fba2fc905 = L.popup({"maxWidth": "100%"});

        
            var html_3a1b0b5d483748b5b57f2c6755b0585d = $(`<div id="html_3a1b0b5d483748b5b57f2c6755b0585d" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 NGLIPAR</div>`)[0];
            popup_29443c7d3c1d4d70bb9d594fba2fc905.setContent(html_3a1b0b5d483748b5b57f2c6755b0585d);
        

        marker_9c4f6b4ee1cf42e09fd9ca1604d57718.bindPopup(popup_29443c7d3c1d4d70bb9d594fba2fc905)
        ;

        
    
    
            var marker_a760bb0174a848b8af57e7460a834ef7 = L.marker(
                [-7.659735, 110.4218733],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_7632457859484419adf0bed5a138ac00 = L.popup({"maxWidth": "100%"});

        
            var html_db6c08f7f8e944378ca3517415013e30 = $(`<div id="html_db6c08f7f8e944378ca3517415013e30" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 PAKEM</div>`)[0];
            popup_7632457859484419adf0bed5a138ac00.setContent(html_db6c08f7f8e944378ca3517415013e30);
        

        marker_a760bb0174a848b8af57e7460a834ef7.bindPopup(popup_7632457859484419adf0bed5a138ac00)
        ;

        
    
    
            var marker_03daa9bf46f0404db038f8b0b64afc0a = L.marker(
                [-7.8457, 110.4275],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_22addf62e9fd486aa3d4d01474fc30ef = L.popup({"maxWidth": "100%"});

        
            var html_d41fd00caff449d7b8bffb2c6b706fff = $(`<div id="html_d41fd00caff449d7b8bffb2c6b706fff" style="width: 100.0%; height: 100.0%;">SMP NEGERI 5 BANGUNTAPAN</div>`)[0];
            popup_22addf62e9fd486aa3d4d01474fc30ef.setContent(html_d41fd00caff449d7b8bffb2c6b706fff);
        

        marker_03daa9bf46f0404db038f8b0b64afc0a.bindPopup(popup_22addf62e9fd486aa3d4d01474fc30ef)
        ;

        
    
    
            var marker_3c2ed309e48f4b3d923f97be9465612f = L.marker(
                [-8.0157, 110.4185],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_f121eeb3974646c99a28622f8b870437 = L.popup({"maxWidth": "100%"});

        
            var html_a709826ee9a14b1491c1a247829d0ae1 = $(`<div id="html_a709826ee9a14b1491c1a247829d0ae1" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 PANGGANG</div>`)[0];
            popup_f121eeb3974646c99a28622f8b870437.setContent(html_a709826ee9a14b1491c1a247829d0ae1);
        

        marker_3c2ed309e48f4b3d923f97be9465612f.bindPopup(popup_f121eeb3974646c99a28622f8b870437)
        ;

        
    
    
            var marker_5d2162cdd81d41b1a570da108bd536fb = L.marker(
                [-7.7829, 110.2174],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_450dd883b1474df38bf644b701323b6a = L.popup({"maxWidth": "100%"});

        
            var html_cdcc6973a50e4b4aae367276eb3adbcf = $(`<div id="html_cdcc6973a50e4b4aae367276eb3adbcf" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 NANGGULAN</div>`)[0];
            popup_450dd883b1474df38bf644b701323b6a.setContent(html_cdcc6973a50e4b4aae367276eb3adbcf);
        

        marker_5d2162cdd81d41b1a570da108bd536fb.bindPopup(popup_450dd883b1474df38bf644b701323b6a)
        ;

        
    
    
            var marker_1db427f9211b42daab89d26cdb695518 = L.marker(
                [-7.9179, 110.3824],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_49a514d200234d7ca647b3f533f6027b = L.popup({"maxWidth": "100%"});

        
            var html_9c961757cc5640d6a0946500d1523c90 = $(`<div id="html_9c961757cc5640d6a0946500d1523c90" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 IMOGIRI</div>`)[0];
            popup_49a514d200234d7ca647b3f533f6027b.setContent(html_9c961757cc5640d6a0946500d1523c90);
        

        marker_1db427f9211b42daab89d26cdb695518.bindPopup(popup_49a514d200234d7ca647b3f533f6027b)
        ;

        
    
    
            var marker_b44b82a6167749d08080709abfc51947 = L.marker(
                [-8.0177, 110.7427],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_75b7e5177bee4502992c9eb487b72147 = L.popup({"maxWidth": "100%"});

        
            var html_a190a39fe8ca49179fd22ba3aa3bcb2d = $(`<div id="html_a190a39fe8ca49179fd22ba3aa3bcb2d" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 PONJONG</div>`)[0];
            popup_75b7e5177bee4502992c9eb487b72147.setContent(html_a190a39fe8ca49179fd22ba3aa3bcb2d);
        

        marker_b44b82a6167749d08080709abfc51947.bindPopup(popup_75b7e5177bee4502992c9eb487b72147)
        ;

        
    
    
            var marker_63cd4e4f669448558d01119ec5500232 = L.marker(
                [-7.6248433, 110.3911716],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_ff9f6182d423495b9b5579daee7fec6c = L.popup({"maxWidth": "100%"});

        
            var html_457dbab7fa094330ae0b986221e92b40 = $(`<div id="html_457dbab7fa094330ae0b986221e92b40" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 TURI</div>`)[0];
            popup_ff9f6182d423495b9b5579daee7fec6c.setContent(html_457dbab7fa094330ae0b986221e92b40);
        

        marker_63cd4e4f669448558d01119ec5500232.bindPopup(popup_ff9f6182d423495b9b5579daee7fec6c)
        ;

        
    
    
            var marker_2b69c2d29811479f9bfa8364fdcfcf2c = L.marker(
                [-7.7776, 110.3754],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_a01f2ee6b52d4ac6b4db530b4b3cd65a = L.popup({"maxWidth": "100%"});

        
            var html_ac2cd38267a74a7fb145986627a48891 = $(`<div id="html_ac2cd38267a74a7fb145986627a48891" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 YOGYAKARTA</div>`)[0];
            popup_a01f2ee6b52d4ac6b4db530b4b3cd65a.setContent(html_ac2cd38267a74a7fb145986627a48891);
        

        marker_2b69c2d29811479f9bfa8364fdcfcf2c.bindPopup(popup_a01f2ee6b52d4ac6b4db530b4b3cd65a)
        ;

        
    
    
            var marker_40abfe581cd4446694095ea49a2bcdf8 = L.marker(
                [-7.8, 110.5301],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_0725f46fc6e048b7badd6ff5e1a3111c = L.popup({"maxWidth": "100%"});

        
            var html_435bf74daa3e4bca9038de3a9c356bdf = $(`<div id="html_435bf74daa3e4bca9038de3a9c356bdf" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 PRAMBANAN</div>`)[0];
            popup_0725f46fc6e048b7badd6ff5e1a3111c.setContent(html_435bf74daa3e4bca9038de3a9c356bdf);
        

        marker_40abfe581cd4446694095ea49a2bcdf8.bindPopup(popup_0725f46fc6e048b7badd6ff5e1a3111c)
        ;

        
    
    
            var marker_60d6114e52014e4fad97b418c75eb78a = L.marker(
                [-7.996055, 110.31358999999999],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_63221f9238fa457182ec4269be404a21 = L.popup({"maxWidth": "100%"});

        
            var html_8c9a84641eaf45ba8d1de6c8981d9019 = $(`<div id="html_8c9a84641eaf45ba8d1de6c8981d9019" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 KRETEK</div>`)[0];
            popup_63221f9238fa457182ec4269be404a21.setContent(html_8c9a84641eaf45ba8d1de6c8981d9019);
        

        marker_60d6114e52014e4fad97b418c75eb78a.bindPopup(popup_63221f9238fa457182ec4269be404a21)
        ;

        
    
    
            var marker_ca770f477d39456da8d665c23b422d3c = L.marker(
                [-7.7148, 110.259],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_2344eb95ced54f8e8ea895ca2309f0cd = L.popup({"maxWidth": "100%"});

        
            var html_4992fad7006e4b6dae42e0c3244a7348 = $(`<div id="html_4992fad7006e4b6dae42e0c3244a7348" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 MINGGIR</div>`)[0];
            popup_2344eb95ced54f8e8ea895ca2309f0cd.setContent(html_4992fad7006e4b6dae42e0c3244a7348);
        

        marker_ca770f477d39456da8d665c23b422d3c.bindPopup(popup_2344eb95ced54f8e8ea895ca2309f0cd)
        ;

        
    
    
            var marker_3b08fe3418c24c19877bc8eb214d15e1 = L.marker(
                [-7.8198, 110.3977],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_c8f250c962394d159b999eee7636f14c = L.popup({"maxWidth": "100%"});

        
            var html_cc0a6f3693af4c5e8bffdec30d6a15df = $(`<div id="html_cc0a6f3693af4c5e8bffdec30d6a15df" style="width: 100.0%; height: 100.0%;">SMP NEGERI 9 YOGYAKARTA</div>`)[0];
            popup_c8f250c962394d159b999eee7636f14c.setContent(html_cc0a6f3693af4c5e8bffdec30d6a15df);
        

        marker_3b08fe3418c24c19877bc8eb214d15e1.bindPopup(popup_c8f250c962394d159b999eee7636f14c)
        ;

        
    
    
            var marker_9422cb1bf9b74672aac662bd5b9d4c4d = L.marker(
                [-7.62595, 110.4542233],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_c154949b43014c459f61d89781f28732 = L.popup({"maxWidth": "100%"});

        
            var html_f892eaff45bc4baaa1a4bcd58cec3a86 = $(`<div id="html_f892eaff45bc4baaa1a4bcd58cec3a86" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 CANGKRINGAN</div>`)[0];
            popup_c154949b43014c459f61d89781f28732.setContent(html_f892eaff45bc4baaa1a4bcd58cec3a86);
        

        marker_9422cb1bf9b74672aac662bd5b9d4c4d.bindPopup(popup_c154949b43014c459f61d89781f28732)
        ;

        
    
    
            var marker_383138574bb34f209d9de4df0bcdfd01 = L.marker(
                [-7.9463, 110.3752],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_5cfbf60bb18f4b19ac78dba4e92db878 = L.popup({"maxWidth": "100%"});

        
            var html_0e01ebf867e14bcebace665b4c0d31d8 = $(`<div id="html_0e01ebf867e14bcebace665b4c0d31d8" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 IMOGIRI</div>`)[0];
            popup_5cfbf60bb18f4b19ac78dba4e92db878.setContent(html_0e01ebf867e14bcebace665b4c0d31d8);
        

        marker_383138574bb34f209d9de4df0bcdfd01.bindPopup(popup_5cfbf60bb18f4b19ac78dba4e92db878)
        ;

        
    
    
            var marker_e93bca6d63b840908356f2f240cdf938 = L.marker(
                [-8.1117, 110.56200000000001],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_833e72976c984d19bd17542b7b37c6c9 = L.popup({"maxWidth": "100%"});

        
            var html_2050ab02b8d344e1baec7aa6ff149bff = $(`<div id="html_2050ab02b8d344e1baec7aa6ff149bff" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 TANJUNGSARI</div>`)[0];
            popup_833e72976c984d19bd17542b7b37c6c9.setContent(html_2050ab02b8d344e1baec7aa6ff149bff);
        

        marker_e93bca6d63b840908356f2f240cdf938.bindPopup(popup_833e72976c984d19bd17542b7b37c6c9)
        ;

        
    
    
            var marker_18abd95cd9104c52a937298f45a13519 = L.marker(
                [-7.701845, 110.2837233],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_6daf4c34a3af43a8adcc97ec30a64185 = L.popup({"maxWidth": "100%"});

        
            var html_f74bef7a4cba4893b63c230790c2d664 = $(`<div id="html_f74bef7a4cba4893b63c230790c2d664" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 TEMPEL</div>`)[0];
            popup_6daf4c34a3af43a8adcc97ec30a64185.setContent(html_f74bef7a4cba4893b63c230790c2d664);
        

        marker_18abd95cd9104c52a937298f45a13519.bindPopup(popup_6daf4c34a3af43a8adcc97ec30a64185)
        ;

        
    
    
            var marker_5f6d263e4bc24fc9a11bad79f64937bd = L.marker(
                [-8.1533, 110.7698],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_0a28c2f8c12443f791913f7f02ce216e = L.popup({"maxWidth": "100%"});

        
            var html_8c7d03f434e24d83a45719f3e1f478e2 = $(`<div id="html_8c7d03f434e24d83a45719f3e1f478e2" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 GIRISUBO</div>`)[0];
            popup_0a28c2f8c12443f791913f7f02ce216e.setContent(html_8c7d03f434e24d83a45719f3e1f478e2);
        

        marker_5f6d263e4bc24fc9a11bad79f64937bd.bindPopup(popup_0a28c2f8c12443f791913f7f02ce216e)
        ;

        
    
    
            var marker_3957cb99bc1a4ed8a2ba57d2739a5c6c = L.marker(
                [-7.880025, 110.61942169999999],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_1cb9d5160c4c40919a278912930870a0 = L.popup({"maxWidth": "100%"});

        
            var html_faf2301a65414ee0991f7d28041c73d4 = $(`<div id="html_faf2301a65414ee0991f7d28041c73d4" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 NGLIPAR</div>`)[0];
            popup_1cb9d5160c4c40919a278912930870a0.setContent(html_faf2301a65414ee0991f7d28041c73d4);
        

        marker_3957cb99bc1a4ed8a2ba57d2739a5c6c.bindPopup(popup_1cb9d5160c4c40919a278912930870a0)
        ;

        
    
    
            var marker_81ffb76d7fab48ca846a92043fe95871 = L.marker(
                [-7.97735, 110.31287830000001],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_6621b4f3783641ba9e0d4319249e56f4 = L.popup({"maxWidth": "100%"});

        
            var html_224d9a56ee0b4047bd37a77cb5e6e8b0 = $(`<div id="html_224d9a56ee0b4047bd37a77cb5e6e8b0" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 KRETEK</div>`)[0];
            popup_6621b4f3783641ba9e0d4319249e56f4.setContent(html_224d9a56ee0b4047bd37a77cb5e6e8b0);
        

        marker_81ffb76d7fab48ca846a92043fe95871.bindPopup(popup_6621b4f3783641ba9e0d4319249e56f4)
        ;

        
    
    
            var marker_5bbef97ed29d405d9133e01757d753a8 = L.marker(
                [-7.8947, 110.3387],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_1cacfd07204642e583bd31eedf0b7a2b = L.popup({"maxWidth": "100%"});

        
            var html_ee763672d05e49e684f08c1d42e164be = $(`<div id="html_ee763672d05e49e684f08c1d42e164be" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 BANTUL</div>`)[0];
            popup_1cacfd07204642e583bd31eedf0b7a2b.setContent(html_ee763672d05e49e684f08c1d42e164be);
        

        marker_5bbef97ed29d405d9133e01757d753a8.bindPopup(popup_1cacfd07204642e583bd31eedf0b7a2b)
        ;

        
    
    
            var marker_09130b625beb4fc49c2466cb52af8213 = L.marker(
                [-7.6603, 110.1576],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_bc58597a2bcb4c9fa4fd68b0227b512b = L.popup({"maxWidth": "100%"});

        
            var html_3a426c171d73465d9636307ad9885655 = $(`<div id="html_3a426c171d73465d9636307ad9885655" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 SAMIGALUH</div>`)[0];
            popup_bc58597a2bcb4c9fa4fd68b0227b512b.setContent(html_3a426c171d73465d9636307ad9885655);
        

        marker_09130b625beb4fc49c2466cb52af8213.bindPopup(popup_bc58597a2bcb4c9fa4fd68b0227b512b)
        ;

        
    
    
            var marker_0197b4f43e1f48f0b2b20c99940678ad = L.marker(
                [-7.7869, 110.3597],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_7fa6423dd2d14a2a99c0f6f3188cfeb6 = L.popup({"maxWidth": "100%"});

        
            var html_aa13eb28a7314fdaa35d069245974b28 = $(`<div id="html_aa13eb28a7314fdaa35d069245974b28" style="width: 100.0%; height: 100.0%;">SMP NEGERI 14 YOGYAKARTA</div>`)[0];
            popup_7fa6423dd2d14a2a99c0f6f3188cfeb6.setContent(html_aa13eb28a7314fdaa35d069245974b28);
        

        marker_0197b4f43e1f48f0b2b20c99940678ad.bindPopup(popup_7fa6423dd2d14a2a99c0f6f3188cfeb6)
        ;

        
    
    
            var marker_d2947aa4654c410cbf5b0e4a9a1d312f = L.marker(
                [-7.668931599999999, 110.4121233],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_e2b0b5c9351045a6b1596e9535c3d849 = L.popup({"maxWidth": "100%"});

        
            var html_30dfc94cbfb046b383c10fe447da7b2e = $(`<div id="html_30dfc94cbfb046b383c10fe447da7b2e" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 PAKEM</div>`)[0];
            popup_e2b0b5c9351045a6b1596e9535c3d849.setContent(html_30dfc94cbfb046b383c10fe447da7b2e);
        

        marker_d2947aa4654c410cbf5b0e4a9a1d312f.bindPopup(popup_e2b0b5c9351045a6b1596e9535c3d849)
        ;

        
    
    
            var marker_a20fcbfb5c1041769312ff19b2031b24 = L.marker(
                [-7.7623, 110.2909],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_3abf532638434464af284349955e9485 = L.popup({"maxWidth": "100%"});

        
            var html_3f8a0b972c7f45d1b6359383937a581a = $(`<div id="html_3f8a0b972c7f45d1b6359383937a581a" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 GODEAN</div>`)[0];
            popup_3abf532638434464af284349955e9485.setContent(html_3f8a0b972c7f45d1b6359383937a581a);
        

        marker_a20fcbfb5c1041769312ff19b2031b24.bindPopup(popup_3abf532638434464af284349955e9485)
        ;

        
    
    
            var marker_aa6b55041ee346eda9e0926a67137f43 = L.marker(
                [-7.8468, 110.3838],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_d7cc91f3ac8949928343bb05ac5666a2 = L.popup({"maxWidth": "100%"});

        
            var html_425ca87660d648ecb289958257b7eb36 = $(`<div id="html_425ca87660d648ecb289958257b7eb36" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 BANGUNTAPAN</div>`)[0];
            popup_d7cc91f3ac8949928343bb05ac5666a2.setContent(html_425ca87660d648ecb289958257b7eb36);
        

        marker_aa6b55041ee346eda9e0926a67137f43.bindPopup(popup_d7cc91f3ac8949928343bb05ac5666a2)
        ;

        
    
    
            var marker_9b385561b4ff481794656b5b46f86ea4 = L.marker(
                [-7.974, 110.4218],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_0f8e6e02867d413497dcb4805a1c4264 = L.popup({"maxWidth": "100%"});

        
            var html_60db03e712fc40f3b12cc2bdf5863688 = $(`<div id="html_60db03e712fc40f3b12cc2bdf5863688" style="width: 100.0%; height: 100.0%;">SMP NEGERI 5 PANGGANG</div>`)[0];
            popup_0f8e6e02867d413497dcb4805a1c4264.setContent(html_60db03e712fc40f3b12cc2bdf5863688);
        

        marker_9b385561b4ff481794656b5b46f86ea4.bindPopup(popup_0f8e6e02867d413497dcb4805a1c4264)
        ;

        
    
    
            var marker_b0b5c15eab054485893598208b164b7c = L.marker(
                [-7.7861, 110.2705],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_c1a6df7231ec4972a18b9c8fb9dca108 = L.popup({"maxWidth": "100%"});

        
            var html_5e9b095ad9b94ce3b0199bccb1dd2419 = $(`<div id="html_5e9b095ad9b94ce3b0199bccb1dd2419" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 MOYUDAN</div>`)[0];
            popup_c1a6df7231ec4972a18b9c8fb9dca108.setContent(html_5e9b095ad9b94ce3b0199bccb1dd2419);
        

        marker_b0b5c15eab054485893598208b164b7c.bindPopup(popup_c1a6df7231ec4972a18b9c8fb9dca108)
        ;

        
    
    
            var marker_07280d2c97104b948c58f7a0f983d5ba = L.marker(
                [-7.8075, 110.1094],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_d3334e9af7b444e0a380f1ed5370ed8e = L.popup({"maxWidth": "100%"});

        
            var html_11c12975ae94492aadb0e09ca2fcf9c0 = $(`<div id="html_11c12975ae94492aadb0e09ca2fcf9c0" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 KOKAP</div>`)[0];
            popup_d3334e9af7b444e0a380f1ed5370ed8e.setContent(html_11c12975ae94492aadb0e09ca2fcf9c0);
        

        marker_07280d2c97104b948c58f7a0f983d5ba.bindPopup(popup_d3334e9af7b444e0a380f1ed5370ed8e)
        ;

        
    
    
            var marker_a9b89f2031164b8bac58f41ddedf2e4f = L.marker(
                [-7.8699433, 110.5236467],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_c800f6afdea04f048a6f3e04e02ecabc = L.popup({"maxWidth": "100%"});

        
            var html_56c88e80e2c343ac8aab2a4e3e9ee001 = $(`<div id="html_56c88e80e2c343ac8aab2a4e3e9ee001" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 PATUK</div>`)[0];
            popup_c800f6afdea04f048a6f3e04e02ecabc.setContent(html_56c88e80e2c343ac8aab2a4e3e9ee001);
        

        marker_a9b89f2031164b8bac58f41ddedf2e4f.bindPopup(popup_c800f6afdea04f048a6f3e04e02ecabc)
        ;

        
    
    
            var marker_cea7d2b7894b4b6abd543d393f827d92 = L.marker(
                [-8.0795, 110.7635],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_31fb3e5694294b1595b5ef6a47d7d1c4 = L.popup({"maxWidth": "100%"});

        
            var html_ed897b03e38049569b860d828e2741f2 = $(`<div id="html_ed897b03e38049569b860d828e2741f2" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 RONGKOP</div>`)[0];
            popup_31fb3e5694294b1595b5ef6a47d7d1c4.setContent(html_ed897b03e38049569b860d828e2741f2);
        

        marker_cea7d2b7894b4b6abd543d393f827d92.bindPopup(popup_31fb3e5694294b1595b5ef6a47d7d1c4)
        ;

        
    
    
            var marker_9f73af4867e8496d81c2c3032232519c = L.marker(
                [-7.7667, 110.4713],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_68f64f0ebaab4453a43a32ee2327dbc8 = L.popup({"maxWidth": "100%"});

        
            var html_2411b422b3e6461caa81ad80132a7350 = $(`<div id="html_2411b422b3e6461caa81ad80132a7350" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 KALASAN</div>`)[0];
            popup_68f64f0ebaab4453a43a32ee2327dbc8.setContent(html_2411b422b3e6461caa81ad80132a7350);
        

        marker_9f73af4867e8496d81c2c3032232519c.bindPopup(popup_68f64f0ebaab4453a43a32ee2327dbc8)
        ;

        
    
    
            var marker_9b8ff617b6ec402ca44eb220ea82dff3 = L.marker(
                [-7.6743, 110.1346],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_ac2f32b69a9146998c0a506ea36dec6c = L.popup({"maxWidth": "100%"});

        
            var html_1f694d2a890940398adc003598795b3c = $(`<div id="html_1f694d2a890940398adc003598795b3c" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 SAMIGALUH</div>`)[0];
            popup_ac2f32b69a9146998c0a506ea36dec6c.setContent(html_1f694d2a890940398adc003598795b3c);
        

        marker_9b8ff617b6ec402ca44eb220ea82dff3.bindPopup(popup_ac2f32b69a9146998c0a506ea36dec6c)
        ;

        
    
    
            var marker_5e2f0a7e7bd0414c9e213f14c72a508e = L.marker(
                [-7.8861, 110.075],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_e207a43702414d07a075ff6524e0fdb2 = L.popup({"maxWidth": "100%"});

        
            var html_a50c512b3b304709966b1d6bb906098f = $(`<div id="html_a50c512b3b304709966b1d6bb906098f" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 TEMON</div>`)[0];
            popup_e207a43702414d07a075ff6524e0fdb2.setContent(html_a50c512b3b304709966b1d6bb906098f);
        

        marker_5e2f0a7e7bd0414c9e213f14c72a508e.bindPopup(popup_e207a43702414d07a075ff6524e0fdb2)
        ;

        
    
    
            var marker_cea4f80769d64f099d1a737c46fd09dc = L.marker(
                [-7.7161, 110.40700000000001],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_cb43a3e6f245497b975cc16c27056fa3 = L.popup({"maxWidth": "100%"});

        
            var html_9c573cd2a27a4691bdec788c41583607 = $(`<div id="html_9c573cd2a27a4691bdec788c41583607" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 NGAGLIK</div>`)[0];
            popup_cb43a3e6f245497b975cc16c27056fa3.setContent(html_9c573cd2a27a4691bdec788c41583607);
        

        marker_cea4f80769d64f099d1a737c46fd09dc.bindPopup(popup_cb43a3e6f245497b975cc16c27056fa3)
        ;

        
    
    
            var marker_c242d60f23cf4dc18775613b81d37962 = L.marker(
                [-7.7816, 110.3169],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_6619a94aadc449abbf2c4d79ab4a9270 = L.popup({"maxWidth": "100%"});

        
            var html_3e558f65ee374ff289f4d84d2e4209f5 = $(`<div id="html_3e558f65ee374ff289f4d84d2e4209f5" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 GODEAN</div>`)[0];
            popup_6619a94aadc449abbf2c4d79ab4a9270.setContent(html_3e558f65ee374ff289f4d84d2e4209f5);
        

        marker_c242d60f23cf4dc18775613b81d37962.bindPopup(popup_6619a94aadc449abbf2c4d79ab4a9270)
        ;

        
    
    
            var marker_4e379ea7192142d39b3902ea5a19b5ad = L.marker(
                [-7.7417, 110.3228],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_d6b588abe20a4d51a49c75be4326f9cd = L.popup({"maxWidth": "100%"});

        
            var html_f2b8e42513ca45e3b4fa7ba9993a8e65 = $(`<div id="html_f2b8e42513ca45e3b4fa7ba9993a8e65" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 MLATI</div>`)[0];
            popup_d6b588abe20a4d51a49c75be4326f9cd.setContent(html_f2b8e42513ca45e3b4fa7ba9993a8e65);
        

        marker_4e379ea7192142d39b3902ea5a19b5ad.bindPopup(popup_d6b588abe20a4d51a49c75be4326f9cd)
        ;

        
    
    
            var marker_ccd948c97e2144d88ab863951ade5cb4 = L.marker(
                [-7.8575, 110.4169],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_c7260391b794449caf0520fecdd3d6ba = L.popup({"maxWidth": "100%"});

        
            var html_a7f5971badcd421eb3e73c8a7096d4df = $(`<div id="html_a7f5971badcd421eb3e73c8a7096d4df" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 BANGUNTAPAN</div>`)[0];
            popup_c7260391b794449caf0520fecdd3d6ba.setContent(html_a7f5971badcd421eb3e73c8a7096d4df);
        

        marker_ccd948c97e2144d88ab863951ade5cb4.bindPopup(popup_c7260391b794449caf0520fecdd3d6ba)
        ;

        
    
    
            var marker_ea8cd7a10fdc4b5ab4a5cc7593334492 = L.marker(
                [-7.8358817, 110.52646829999999],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_56b85cf76df149caabf6567afcf40e70 = L.popup({"maxWidth": "100%"});

        
            var html_e1335333310a48e4ad1ce5c207f851d5 = $(`<div id="html_e1335333310a48e4ad1ce5c207f851d5" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 PATUK</div>`)[0];
            popup_56b85cf76df149caabf6567afcf40e70.setContent(html_e1335333310a48e4ad1ce5c207f851d5);
        

        marker_ea8cd7a10fdc4b5ab4a5cc7593334492.bindPopup(popup_56b85cf76df149caabf6567afcf40e70)
        ;

        
    
    
            var marker_3d2f5c21f2b244679043789e617df325 = L.marker(
                [-7.7586, 110.4489],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_4c9a7762a14b4b408dc5220ab8e1d5f4 = L.popup({"maxWidth": "100%"});

        
            var html_040e67b436e84c27aac4c2e3fc415341 = $(`<div id="html_040e67b436e84c27aac4c2e3fc415341" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 KALASAN</div>`)[0];
            popup_4c9a7762a14b4b408dc5220ab8e1d5f4.setContent(html_040e67b436e84c27aac4c2e3fc415341);
        

        marker_3d2f5c21f2b244679043789e617df325.bindPopup(popup_4c9a7762a14b4b408dc5220ab8e1d5f4)
        ;

        
    
    
            var marker_e017d2b7cb5e4ab9864d4edbaac4e58d = L.marker(
                [-7.8611, 110.3537],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_a7f9fdbb6f53452e91fd1359f7de5621 = L.popup({"maxWidth": "100%"});

        
            var html_860cc589df6d46e09b6be435008a1178 = $(`<div id="html_860cc589df6d46e09b6be435008a1178" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 SEWON</div>`)[0];
            popup_a7f9fdbb6f53452e91fd1359f7de5621.setContent(html_860cc589df6d46e09b6be435008a1178);
        

        marker_e017d2b7cb5e4ab9864d4edbaac4e58d.bindPopup(popup_a7f9fdbb6f53452e91fd1359f7de5621)
        ;

        
    
    
            var marker_1500e32d6b40454799958ece325b97fc = L.marker(
                [-7.8658, 110.6602],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_677587f4a6504cb2b52695d9f5a98214 = L.popup({"maxWidth": "100%"});

        
            var html_4a18050960424ab4b85cf1bb4ecd6c50 = $(`<div id="html_4a18050960424ab4b85cf1bb4ecd6c50" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 NGLIPAR</div>`)[0];
            popup_677587f4a6504cb2b52695d9f5a98214.setContent(html_4a18050960424ab4b85cf1bb4ecd6c50);
        

        marker_1500e32d6b40454799958ece325b97fc.bindPopup(popup_677587f4a6504cb2b52695d9f5a98214)
        ;

        
    
    
            var marker_82d9e6417e9146d4a329fdfbabe809d1 = L.marker(
                [-7.6876, 110.3878],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_50703fdc2ead47c493c3daa9acbbae01 = L.popup({"maxWidth": "100%"});

        
            var html_ff51ebb9ea264ad2b1c5eb8291a02784 = $(`<div id="html_ff51ebb9ea264ad2b1c5eb8291a02784" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 NGAGLIK</div>`)[0];
            popup_50703fdc2ead47c493c3daa9acbbae01.setContent(html_ff51ebb9ea264ad2b1c5eb8291a02784);
        

        marker_82d9e6417e9146d4a329fdfbabe809d1.bindPopup(popup_50703fdc2ead47c493c3daa9acbbae01)
        ;

        
    
    
            var marker_3befe7fbf07945779920a6069feb1604 = L.marker(
                [-7.8632, 110.6365],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_1b1500db66124675a1b69438aa6054c2 = L.popup({"maxWidth": "100%"});

        
            var html_6e34d8e8c52b40369d66adb5d753dd64 = $(`<div id="html_6e34d8e8c52b40369d66adb5d753dd64" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 NGLIPAR</div>`)[0];
            popup_1b1500db66124675a1b69438aa6054c2.setContent(html_6e34d8e8c52b40369d66adb5d753dd64);
        

        marker_3befe7fbf07945779920a6069feb1604.bindPopup(popup_1b1500db66124675a1b69438aa6054c2)
        ;

        
    
    
            var marker_112655c417194ad4996c741e7298d2e7 = L.marker(
                [-7.8197, 110.3603],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_852847f0cb794bce87bf8b0a5ed655b9 = L.popup({"maxWidth": "100%"});

        
            var html_c3d14ef663eb42d68768b2842382ad87 = $(`<div id="html_c3d14ef663eb42d68768b2842382ad87" style="width: 100.0%; height: 100.0%;">SMP NEGERI 13 YOGYAKARTA</div>`)[0];
            popup_852847f0cb794bce87bf8b0a5ed655b9.setContent(html_c3d14ef663eb42d68768b2842382ad87);
        

        marker_112655c417194ad4996c741e7298d2e7.bindPopup(popup_852847f0cb794bce87bf8b0a5ed655b9)
        ;

        
    
    
            var marker_0ec8fa551814468eb2d1726764f114ab = L.marker(
                [-7.8716, 110.1962],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_af3a5452e41a4cee9f87320c3f45cf85 = L.popup({"maxWidth": "100%"});

        
            var html_048219afaf57408db4f096a9e01b066a = $(`<div id="html_048219afaf57408db4f096a9e01b066a" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 PENGASIH</div>`)[0];
            popup_af3a5452e41a4cee9f87320c3f45cf85.setContent(html_048219afaf57408db4f096a9e01b066a);
        

        marker_0ec8fa551814468eb2d1726764f114ab.bindPopup(popup_af3a5452e41a4cee9f87320c3f45cf85)
        ;

        
    
    
            var marker_8466bbb088434d6aa03f47694ea80033 = L.marker(
                [-7.9017, 110.2992],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_84a0d5c7445040e4aef4595e467402a2 = L.popup({"maxWidth": "100%"});

        
            var html_8767308c316443bf950ac996e7fc3cd7 = $(`<div id="html_8767308c316443bf950ac996e7fc3cd7" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 PANDAK</div>`)[0];
            popup_84a0d5c7445040e4aef4595e467402a2.setContent(html_8767308c316443bf950ac996e7fc3cd7);
        

        marker_8466bbb088434d6aa03f47694ea80033.bindPopup(popup_84a0d5c7445040e4aef4595e467402a2)
        ;

        
    
    
            var marker_d3ab25152f5b4d6d93109398b6ec9e0e = L.marker(
                [-7.8582, 110.2727],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_fa9b970b01c845f6a61908dc6861ed52 = L.popup({"maxWidth": "100%"});

        
            var html_8f41edfe0c8e4add820f7485b1ebe1f5 = $(`<div id="html_8f41edfe0c8e4add820f7485b1ebe1f5" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 PAJANGAN</div>`)[0];
            popup_fa9b970b01c845f6a61908dc6861ed52.setContent(html_8f41edfe0c8e4add820f7485b1ebe1f5);
        

        marker_d3ab25152f5b4d6d93109398b6ec9e0e.bindPopup(popup_fa9b970b01c845f6a61908dc6861ed52)
        ;

        
    
    
            var marker_a5c7e16e094d4bc3b181c1e7630be673 = L.marker(
                [-7.96505, 110.6046133],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_a55748526a07476995a71cf7f1299ab7 = L.popup({"maxWidth": "100%"});

        
            var html_417a52a60dca434fb208749c1be02adc = $(`<div id="html_417a52a60dca434fb208749c1be02adc" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 WONOSARI</div>`)[0];
            popup_a55748526a07476995a71cf7f1299ab7.setContent(html_417a52a60dca434fb208749c1be02adc);
        

        marker_a5c7e16e094d4bc3b181c1e7630be673.bindPopup(popup_a55748526a07476995a71cf7f1299ab7)
        ;

        
    
    
            var marker_0270909299ed4442b3ff0b352940c0af = L.marker(
                [-7.7865, 110.36],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_42b7083840f54b58a16f4d3df23a3dd5 = L.popup({"maxWidth": "100%"});

        
            var html_3b992152b6404316b18275607ff1def6 = $(`<div id="html_3b992152b6404316b18275607ff1def6" style="width: 100.0%; height: 100.0%;">SMP NEGERI 12 YOGYAKARTA</div>`)[0];
            popup_42b7083840f54b58a16f4d3df23a3dd5.setContent(html_3b992152b6404316b18275607ff1def6);
        

        marker_0270909299ed4442b3ff0b352940c0af.bindPopup(popup_42b7083840f54b58a16f4d3df23a3dd5)
        ;

        
    
    
            var marker_ade9cb8930694e5a88e6509db1379043 = L.marker(
                [-7.8436, 110.1682],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_98f6b11ba74541eaaf9a0899fdb9843b = L.popup({"maxWidth": "100%"});

        
            var html_f09eea5285444031bc03d6a291487820 = $(`<div id="html_f09eea5285444031bc03d6a291487820" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 PENGASIH</div>`)[0];
            popup_98f6b11ba74541eaaf9a0899fdb9843b.setContent(html_f09eea5285444031bc03d6a291487820);
        

        marker_ade9cb8930694e5a88e6509db1379043.bindPopup(popup_98f6b11ba74541eaaf9a0899fdb9843b)
        ;

        
    
    
            var marker_dc0947c2f84147bbaa7693a58228736d = L.marker(
                [-7.7227, 110.3086],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_ddeac47beee646f5bea1aa92c27d47e1 = L.popup({"maxWidth": "100%"});

        
            var html_8cac314759f244c5beaa3f7ddd5dc698 = $(`<div id="html_8cac314759f244c5beaa3f7ddd5dc698" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 SEYEGAN</div>`)[0];
            popup_ddeac47beee646f5bea1aa92c27d47e1.setContent(html_8cac314759f244c5beaa3f7ddd5dc698);
        

        marker_dc0947c2f84147bbaa7693a58228736d.bindPopup(popup_ddeac47beee646f5bea1aa92c27d47e1)
        ;

        
    
    
            var marker_0d498c12b7d840808eb1e8ba080b3fbb = L.marker(
                [-7.7722, 110.1849],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_89fdf30d89bb46ac8c522e81c303b86a = L.popup({"maxWidth": "100%"});

        
            var html_36083a21fdad4a488ec62a9ee10f56e1 = $(`<div id="html_36083a21fdad4a488ec62a9ee10f56e1" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 GIRIMULYO</div>`)[0];
            popup_89fdf30d89bb46ac8c522e81c303b86a.setContent(html_36083a21fdad4a488ec62a9ee10f56e1);
        

        marker_0d498c12b7d840808eb1e8ba080b3fbb.bindPopup(popup_89fdf30d89bb46ac8c522e81c303b86a)
        ;

        
    
    
            var marker_98b8851506034065a4f5f312c5b93ddc = L.marker(
                [-7.6837667000000005, 110.339],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_f302b23d51374818ba0d10d90236d16c = L.popup({"maxWidth": "100%"});

        
            var html_0346fecebc0a4f318133a1ec5d81b1f1 = $(`<div id="html_0346fecebc0a4f318133a1ec5d81b1f1" style="width: 100.0%; height: 100.0%;">SMP Negeri 1 Sleman</div>`)[0];
            popup_f302b23d51374818ba0d10d90236d16c.setContent(html_0346fecebc0a4f318133a1ec5d81b1f1);
        

        marker_98b8851506034065a4f5f312c5b93ddc.bindPopup(popup_f302b23d51374818ba0d10d90236d16c)
        ;

        
    
    
            var marker_4a0e1b7a9afc425e972c65e0f0572849 = L.marker(
                [-7.8257, 110.3271],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_1a7a40c1ff41439e9ec57fc833753332 = L.popup({"maxWidth": "100%"});

        
            var html_007c2b5e2f414f37bcf9f0bb548ee49e = $(`<div id="html_007c2b5e2f414f37bcf9f0bb548ee49e" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 KASIHAN</div>`)[0];
            popup_1a7a40c1ff41439e9ec57fc833753332.setContent(html_007c2b5e2f414f37bcf9f0bb548ee49e);
        

        marker_4a0e1b7a9afc425e972c65e0f0572849.bindPopup(popup_1a7a40c1ff41439e9ec57fc833753332)
        ;

        
    
    
            var marker_3da9118ba10d47b28a539a1f8fb0ed03 = L.marker(
                [-7.9127367, 110.5565],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_43a7e5ace9fe45e282c490e34245a17f = L.popup({"maxWidth": "100%"});

        
            var html_c991073ce7844461b2b0083df2599c82 = $(`<div id="html_c991073ce7844461b2b0083df2599c82" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 PLAYEN</div>`)[0];
            popup_43a7e5ace9fe45e282c490e34245a17f.setContent(html_c991073ce7844461b2b0083df2599c82);
        

        marker_3da9118ba10d47b28a539a1f8fb0ed03.bindPopup(popup_43a7e5ace9fe45e282c490e34245a17f)
        ;

        
    
    
            var marker_916b7baf54d5404993daf025b0326c49 = L.marker(
                [-7.8452, 110.23700000000001],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_194f0601e6214169b6b005fa260ce887 = L.popup({"maxWidth": "100%"});

        
            var html_e1a55668e7c9418aaa00c62ebfbc41b1 = $(`<div id="html_e1a55668e7c9418aaa00c62ebfbc41b1" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 SEDAYU</div>`)[0];
            popup_194f0601e6214169b6b005fa260ce887.setContent(html_e1a55668e7c9418aaa00c62ebfbc41b1);
        

        marker_916b7baf54d5404993daf025b0326c49.bindPopup(popup_194f0601e6214169b6b005fa260ce887)
        ;

        
    
    
            var marker_95f49b822a9943d584d69edb1a0573dd = L.marker(
                [-7.8004, 110.3393],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_a3fa1890b03d449b90365212ee6bee02 = L.popup({"maxWidth": "100%"});

        
            var html_7d8621c850404a4d934fb3e6fd9673e3 = $(`<div id="html_7d8621c850404a4d934fb3e6fd9673e3" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 KASIHAN</div>`)[0];
            popup_a3fa1890b03d449b90365212ee6bee02.setContent(html_7d8621c850404a4d934fb3e6fd9673e3);
        

        marker_95f49b822a9943d584d69edb1a0573dd.bindPopup(popup_a3fa1890b03d449b90365212ee6bee02)
        ;

        
    
    
            var marker_3a5c6fd682bd48948c57f614daeccc23 = L.marker(
                [-7.9432217000000005, 110.6402217],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_6398ccb68deb464baca957ca4218515e = L.popup({"maxWidth": "100%"});

        
            var html_54bbe638c49c4d99a03889d29ccb3c8d = $(`<div id="html_54bbe638c49c4d99a03889d29ccb3c8d" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 KARANGMOJO</div>`)[0];
            popup_6398ccb68deb464baca957ca4218515e.setContent(html_54bbe638c49c4d99a03889d29ccb3c8d);
        

        marker_3a5c6fd682bd48948c57f614daeccc23.bindPopup(popup_6398ccb68deb464baca957ca4218515e)
        ;

        
    
    
            var marker_2518a921393f4faa9474a46f6c07413e = L.marker(
                [-7.8689, 110.3908],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_0611989d06994c8586e361644960884b = L.popup({"maxWidth": "100%"});

        
            var html_c9888b7b66554dfa9d68d0e6287abcf8 = $(`<div id="html_c9888b7b66554dfa9d68d0e6287abcf8" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 PLERET</div>`)[0];
            popup_0611989d06994c8586e361644960884b.setContent(html_c9888b7b66554dfa9d68d0e6287abcf8);
        

        marker_2518a921393f4faa9474a46f6c07413e.bindPopup(popup_0611989d06994c8586e361644960884b)
        ;

        
    
    
            var marker_7920b39fa5004c62ae4645d94ad276b9 = L.marker(
                [-7.9671, 110.5986],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_a07c6da36aa44d2abd9d21b6df19efbb = L.popup({"maxWidth": "100%"});

        
            var html_919148b67efa4626adf0a198dbb7f4f3 = $(`<div id="html_919148b67efa4626adf0a198dbb7f4f3" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 WONOSARI</div>`)[0];
            popup_a07c6da36aa44d2abd9d21b6df19efbb.setContent(html_919148b67efa4626adf0a198dbb7f4f3);
        

        marker_7920b39fa5004c62ae4645d94ad276b9.bindPopup(popup_a07c6da36aa44d2abd9d21b6df19efbb)
        ;

        
    
    
            var marker_4b40cfdb4fc34fa1a05b43d9a58c3fba = L.marker(
                [-7.8501, 110.3451],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_518a5b44ab814d6f975ae2521e26f77c = L.popup({"maxWidth": "100%"});

        
            var html_b86047caf0a540df9d7f3e15096bfe3d = $(`<div id="html_b86047caf0a540df9d7f3e15096bfe3d" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 SEWON</div>`)[0];
            popup_518a5b44ab814d6f975ae2521e26f77c.setContent(html_b86047caf0a540df9d7f3e15096bfe3d);
        

        marker_4b40cfdb4fc34fa1a05b43d9a58c3fba.bindPopup(popup_518a5b44ab814d6f975ae2521e26f77c)
        ;

        
    
    
            var marker_33b037fcbd9f46feab08e5e4f0387c54 = L.marker(
                [-7.8048, 110.4446],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_9aec4e82bec0499ab4a497ad801926c2 = L.popup({"maxWidth": "100%"});

        
            var html_9c09be8c7724473c93cda67fe10ee39f = $(`<div id="html_9c09be8c7724473c93cda67fe10ee39f" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 BERBAH</div>`)[0];
            popup_9aec4e82bec0499ab4a497ad801926c2.setContent(html_9c09be8c7724473c93cda67fe10ee39f);
        

        marker_33b037fcbd9f46feab08e5e4f0387c54.bindPopup(popup_9aec4e82bec0499ab4a497ad801926c2)
        ;

        
    
    
            var marker_5e2ac70e06824a3dbb2da3fe52b72d40 = L.marker(
                [-7.7452, 110.3373],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_c5c0eb82b77846d8a0292f86988ef440 = L.popup({"maxWidth": "100%"});

        
            var html_6413c5eb0209486c8bce9103538bc643 = $(`<div id="html_6413c5eb0209486c8bce9103538bc643" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 MLATI</div>`)[0];
            popup_c5c0eb82b77846d8a0292f86988ef440.setContent(html_6413c5eb0209486c8bce9103538bc643);
        

        marker_5e2ac70e06824a3dbb2da3fe52b72d40.bindPopup(popup_c5c0eb82b77846d8a0292f86988ef440)
        ;

        
    
    
            var marker_1cc93b472b084e3e9551fd4a5c1152dd = L.marker(
                [-8.0819, 110.4858],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_4e658da14bd1400f873192b7251a1e4a = L.popup({"maxWidth": "100%"});

        
            var html_711f274a16be4eb99bca2e4fc981a2c9 = $(`<div id="html_711f274a16be4eb99bca2e4fc981a2c9" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 SAPTOSARI</div>`)[0];
            popup_4e658da14bd1400f873192b7251a1e4a.setContent(html_711f274a16be4eb99bca2e4fc981a2c9);
        

        marker_1cc93b472b084e3e9551fd4a5c1152dd.bindPopup(popup_4e658da14bd1400f873192b7251a1e4a)
        ;

        
    
    
            var marker_633f41569b9c414f90cba3842fe56e30 = L.marker(
                [-7.7916, 110.3762],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_acb7ba95133d4b46a080f4bae85fa841 = L.popup({"maxWidth": "100%"});

        
            var html_9a7c9298f00b47cfb7f57857daf46770 = $(`<div id="html_9a7c9298f00b47cfb7f57857daf46770" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 YOGYAKARTA</div>`)[0];
            popup_acb7ba95133d4b46a080f4bae85fa841.setContent(html_9a7c9298f00b47cfb7f57857daf46770);
        

        marker_633f41569b9c414f90cba3842fe56e30.bindPopup(popup_acb7ba95133d4b46a080f4bae85fa841)
        ;

        
    
    
            var marker_8b500ec50f9f4b0d984555c44b0311a0 = L.marker(
                [-7.6724, 110.1285],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_71cc41e043a6401d91f4d0a66658570c = L.popup({"maxWidth": "100%"});

        
            var html_cde5b9a40aeb4365b29493246100a88d = $(`<div id="html_cde5b9a40aeb4365b29493246100a88d" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 SAMIGALUH</div>`)[0];
            popup_71cc41e043a6401d91f4d0a66658570c.setContent(html_cde5b9a40aeb4365b29493246100a88d);
        

        marker_8b500ec50f9f4b0d984555c44b0311a0.bindPopup(popup_71cc41e043a6401d91f4d0a66658570c)
        ;

        
    
    
            var marker_f9a7270f4d854679a53984b8c5525690 = L.marker(
                [-8.002373299999999, 110.509125],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_0155ae5853a5432d929ab045274b30f3 = L.popup({"maxWidth": "100%"});

        
            var html_b63b558bf981493fbb3c76af5b1c1556 = $(`<div id="html_b63b558bf981493fbb3c76af5b1c1556" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 PALIYAN</div>`)[0];
            popup_0155ae5853a5432d929ab045274b30f3.setContent(html_b63b558bf981493fbb3c76af5b1c1556);
        

        marker_f9a7270f4d854679a53984b8c5525690.bindPopup(popup_0155ae5853a5432d929ab045274b30f3)
        ;

        
    
    
            var marker_33cbcf5223b545d588348fdf1fd9bb4c = L.marker(
                [-8.0134, 110.5875],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_53cfe468faed4f95b60cc3b2647c72ea = L.popup({"maxWidth": "100%"});

        
            var html_a84167f369c9473593acd53d0be829fa = $(`<div id="html_a84167f369c9473593acd53d0be829fa" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 WONOSARI</div>`)[0];
            popup_53cfe468faed4f95b60cc3b2647c72ea.setContent(html_a84167f369c9473593acd53d0be829fa);
        

        marker_33cbcf5223b545d588348fdf1fd9bb4c.bindPopup(popup_53cfe468faed4f95b60cc3b2647c72ea)
        ;

        
    
    
            var marker_7e614b90c25748f5afcc2af4a8138030 = L.marker(
                [-7.9565, 110.3048],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_46f23581063e4b959b7f8d6b45bb990f = L.popup({"maxWidth": "100%"});

        
            var html_84309667071a4e3e8464bf58cc2cab35 = $(`<div id="html_84309667071a4e3e8464bf58cc2cab35" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 BAMBANGLIPURO</div>`)[0];
            popup_46f23581063e4b959b7f8d6b45bb990f.setContent(html_84309667071a4e3e8464bf58cc2cab35);
        

        marker_7e614b90c25748f5afcc2af4a8138030.bindPopup(popup_46f23581063e4b959b7f8d6b45bb990f)
        ;

        
    
    
            var marker_9a7f5980dc8146b8abd07a675494b461 = L.marker(
                [-7.8373, 110.47200000000001],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_d32188147a824185acf7f5ff40d8697f = L.popup({"maxWidth": "100%"});

        
            var html_883081a0a1444e7eaa55b6c97ef5924b = $(`<div id="html_883081a0a1444e7eaa55b6c97ef5924b" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 PIYUNGAN</div>`)[0];
            popup_d32188147a824185acf7f5ff40d8697f.setContent(html_883081a0a1444e7eaa55b6c97ef5924b);
        

        marker_9a7f5980dc8146b8abd07a675494b461.bindPopup(popup_d32188147a824185acf7f5ff40d8697f)
        ;

        
    
    
            var marker_ae392337f97f4ab6b0272126e70e67e4 = L.marker(
                [-7.7915, 110.3715],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_d233128c7ec946e9929503f33f474215 = L.popup({"maxWidth": "100%"});

        
            var html_f1447508a90e4b31b48603e4e8bd27f7 = $(`<div id="html_f1447508a90e4b31b48603e4e8bd27f7" style="width: 100.0%; height: 100.0%;">SMP NEGERI 15 YOGYAKARTA</div>`)[0];
            popup_d233128c7ec946e9929503f33f474215.setContent(html_f1447508a90e4b31b48603e4e8bd27f7);
        

        marker_ae392337f97f4ab6b0272126e70e67e4.bindPopup(popup_d233128c7ec946e9929503f33f474215)
        ;

        
    
    
            var marker_213d58b09bd447eda79c2d9df6437a30 = L.marker(
                [-7.9993, 110.462],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_f25a1c7a103f4d35961c27f10ac27819 = L.popup({"maxWidth": "100%"});

        
            var html_b572eb26bcda41a48f974b8e5efffb41 = $(`<div id="html_b572eb26bcda41a48f974b8e5efffb41" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 PANGGANG</div>`)[0];
            popup_f25a1c7a103f4d35961c27f10ac27819.setContent(html_b572eb26bcda41a48f974b8e5efffb41);
        

        marker_213d58b09bd447eda79c2d9df6437a30.bindPopup(popup_f25a1c7a103f4d35961c27f10ac27819)
        ;

        
    
    
            var marker_279c97bf1b09440babfa6994d02d9d56 = L.marker(
                [-7.6369867, 110.3518017],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_63b9d0c86bbe4c20a6dd4d69f266b6ec = L.popup({"maxWidth": "100%"});

        
            var html_9311605dcf9b4f3190925feddfc9f068 = $(`<div id="html_9311605dcf9b4f3190925feddfc9f068" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 TEMPEL</div>`)[0];
            popup_63b9d0c86bbe4c20a6dd4d69f266b6ec.setContent(html_9311605dcf9b4f3190925feddfc9f068);
        

        marker_279c97bf1b09440babfa6994d02d9d56.bindPopup(popup_63b9d0c86bbe4c20a6dd4d69f266b6ec)
        ;

        
    
    
            var marker_2b2e46f612554e5e9af703a9f23c89bd = L.marker(
                [-7.8035, 110.6329],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_c68480468f8c466c96a493ea5555b8ec = L.popup({"maxWidth": "100%"});

        
            var html_d12c21973e414ea7812c86e4635211f1 = $(`<div id="html_d12c21973e414ea7812c86e4635211f1" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 GEDANGSARI</div>`)[0];
            popup_c68480468f8c466c96a493ea5555b8ec.setContent(html_d12c21973e414ea7812c86e4635211f1);
        

        marker_2b2e46f612554e5e9af703a9f23c89bd.bindPopup(popup_c68480468f8c466c96a493ea5555b8ec)
        ;

        
    
    
            var marker_b5a3b842f27148c9800e3e913ba7efac = L.marker(
                [-7.9284, 110.7143],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_b6b39faf0e6841a5a275c2a815f79a42 = L.popup({"maxWidth": "100%"});

        
            var html_b7b39a4a31774ef28bbffce60786af6a = $(`<div id="html_b7b39a4a31774ef28bbffce60786af6a" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 PONJONG</div>`)[0];
            popup_b6b39faf0e6841a5a275c2a815f79a42.setContent(html_b7b39a4a31774ef28bbffce60786af6a);
        

        marker_b5a3b842f27148c9800e3e913ba7efac.bindPopup(popup_b6b39faf0e6841a5a275c2a815f79a42)
        ;

        
    
    
            var marker_f6cb169b86dd4744800b548d86bce82c = L.marker(
                [-7.9445, 110.3233],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_5da576eb17f94688af41c648d37df480 = L.popup({"maxWidth": "100%"});

        
            var html_686e2414cae6468c9e6de968bf45a09d = $(`<div id="html_686e2414cae6468c9e6de968bf45a09d" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 BAMBANGLIPURO</div>`)[0];
            popup_5da576eb17f94688af41c648d37df480.setContent(html_686e2414cae6468c9e6de968bf45a09d);
        

        marker_f6cb169b86dd4744800b548d86bce82c.bindPopup(popup_5da576eb17f94688af41c648d37df480)
        ;

        
    
    
            var marker_ee188f6a28194543b0650001bd0bb289 = L.marker(
                [-7.8289, 110.0703],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_cfa166e7dbf34bb7934b9ac9ca7858a5 = L.popup({"maxWidth": "100%"});

        
            var html_76184651943a447c9f432e7e912e5853 = $(`<div id="html_76184651943a447c9f432e7e912e5853" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 KOKAP</div>`)[0];
            popup_cfa166e7dbf34bb7934b9ac9ca7858a5.setContent(html_76184651943a447c9f432e7e912e5853);
        

        marker_ee188f6a28194543b0650001bd0bb289.bindPopup(popup_cfa166e7dbf34bb7934b9ac9ca7858a5)
        ;

        
    
    
            var marker_ce1c1c854d9d4bc1a3162b93c7f2c81e = L.marker(
                [-7.6993, 110.4463],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_9389ab3f364d4a68aaccbbfec35f9d3b = L.popup({"maxWidth": "100%"});

        
            var html_350ba40018e2497095e1b92f53253ef3 = $(`<div id="html_350ba40018e2497095e1b92f53253ef3" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 NGEMPLAK</div>`)[0];
            popup_9389ab3f364d4a68aaccbbfec35f9d3b.setContent(html_350ba40018e2497095e1b92f53253ef3);
        

        marker_ce1c1c854d9d4bc1a3162b93c7f2c81e.bindPopup(popup_9389ab3f364d4a68aaccbbfec35f9d3b)
        ;

        
    
    
            var marker_6933b25b3ab54eaf919ef5cf1d43870f = L.marker(
                [-8.1866, 110.8313],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_8d4e06d63d3944df93269b201367a7d9 = L.popup({"maxWidth": "100%"});

        
            var html_f757c4085e974d739f0a29b607764e42 = $(`<div id="html_f757c4085e974d739f0a29b607764e42" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 GIRISUBO</div>`)[0];
            popup_8d4e06d63d3944df93269b201367a7d9.setContent(html_f757c4085e974d739f0a29b607764e42);
        

        marker_6933b25b3ab54eaf919ef5cf1d43870f.bindPopup(popup_8d4e06d63d3944df93269b201367a7d9)
        ;

        
    
    
            var marker_205ed7186f8c437da883a27c976eda26 = L.marker(
                [-7.945153299999999, 110.5527233],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_1b63bb00b52d406593a2527d9242b332 = L.popup({"maxWidth": "100%"});

        
            var html_31fb928338b44cffb90bccc861284310 = $(`<div id="html_31fb928338b44cffb90bccc861284310" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 PLAYEN</div>`)[0];
            popup_1b63bb00b52d406593a2527d9242b332.setContent(html_31fb928338b44cffb90bccc861284310);
        

        marker_205ed7186f8c437da883a27c976eda26.bindPopup(popup_1b63bb00b52d406593a2527d9242b332)
        ;

        
    
    
            var marker_e9efefdd4e9642fb81fb7f95034b387d = L.marker(
                [-7.8563367, 110.1578433],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_0e6121ef91e744baa576063dbb5aa480 = L.popup({"maxWidth": "100%"});

        
            var html_831bba224500419db00ad3869b745987 = $(`<div id="html_831bba224500419db00ad3869b745987" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 WATES</div>`)[0];
            popup_0e6121ef91e744baa576063dbb5aa480.setContent(html_831bba224500419db00ad3869b745987);
        

        marker_e9efefdd4e9642fb81fb7f95034b387d.bindPopup(popup_0e6121ef91e744baa576063dbb5aa480)
        ;

        
    
    
            var marker_453c699e88cb44d4ab451cd7c64ecc2d = L.marker(
                [-7.9064, 110.3145],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_c082c45f0f30432c9fdf80308dae36c2 = L.popup({"maxWidth": "100%"});

        
            var html_1a13f1fdd5a444c08b04bc4a997983e1 = $(`<div id="html_1a13f1fdd5a444c08b04bc4a997983e1" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 PANDAK</div>`)[0];
            popup_c082c45f0f30432c9fdf80308dae36c2.setContent(html_1a13f1fdd5a444c08b04bc4a997983e1);
        

        marker_453c699e88cb44d4ab451cd7c64ecc2d.bindPopup(popup_c082c45f0f30432c9fdf80308dae36c2)
        ;

        
    
    
            var marker_c825d42a7a01441093fa7a8348debd2f = L.marker(
                [-7.8383, 110.22],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_eb1cdb7e5b5d4a9a90cfb679ec7ee05e = L.popup({"maxWidth": "100%"});

        
            var html_87d60340891340759859bfd96f601ad4 = $(`<div id="html_87d60340891340759859bfd96f601ad4" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 SENTOLO</div>`)[0];
            popup_eb1cdb7e5b5d4a9a90cfb679ec7ee05e.setContent(html_87d60340891340759859bfd96f601ad4);
        

        marker_c825d42a7a01441093fa7a8348debd2f.bindPopup(popup_eb1cdb7e5b5d4a9a90cfb679ec7ee05e)
        ;

        
    
    
            var marker_c2b39481e3d0480f8fc8bdd1a314b6de = L.marker(
                [-7.8628, 110.7224],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_a17e664033874f47b18e646e451653a2 = L.popup({"maxWidth": "100%"});

        
            var html_79510ea8ebac4135b8ce3422b993bc35 = $(`<div id="html_79510ea8ebac4135b8ce3422b993bc35" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 SEMIN</div>`)[0];
            popup_a17e664033874f47b18e646e451653a2.setContent(html_79510ea8ebac4135b8ce3422b993bc35);
        

        marker_c2b39481e3d0480f8fc8bdd1a314b6de.bindPopup(popup_a17e664033874f47b18e646e451653a2)
        ;

        
    
    
            var marker_d802a07041a4473abea63e10c5aba490 = L.marker(
                [-8.0584, 110.6532],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_86bc610dbb6d4e34b98aac7eaf933e5b = L.popup({"maxWidth": "100%"});

        
            var html_aa9b7f2d384f4dbfb4aba8d61a63def7 = $(`<div id="html_aa9b7f2d384f4dbfb4aba8d61a63def7" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 SEMANU</div>`)[0];
            popup_86bc610dbb6d4e34b98aac7eaf933e5b.setContent(html_aa9b7f2d384f4dbfb4aba8d61a63def7);
        

        marker_d802a07041a4473abea63e10c5aba490.bindPopup(popup_86bc610dbb6d4e34b98aac7eaf933e5b)
        ;

        
    
    
            var marker_fe89f72bbc8b404ca09b5518e074bcd9 = L.marker(
                [-7.8833, 110.4141],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_41ae4d4df4b348cdae707b68cb914541 = L.popup({"maxWidth": "100%"});

        
            var html_96a3b1030f9945f48a7d62dea23879ea = $(`<div id="html_96a3b1030f9945f48a7d62dea23879ea" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 PLERET</div>`)[0];
            popup_41ae4d4df4b348cdae707b68cb914541.setContent(html_96a3b1030f9945f48a7d62dea23879ea);
        

        marker_fe89f72bbc8b404ca09b5518e074bcd9.bindPopup(popup_41ae4d4df4b348cdae707b68cb914541)
        ;

        
    
    
            var marker_f3cbefab8992415daaf670278d70c2bc = L.marker(
                [-8.0949, 110.6115],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_46693c85e73b46d0b572461131cc81c5 = L.popup({"maxWidth": "100%"});

        
            var html_f9dfff8fcacd448da5761ae2d1f1c55d = $(`<div id="html_f9dfff8fcacd448da5761ae2d1f1c55d" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 TANJUNGSARI</div>`)[0];
            popup_46693c85e73b46d0b572461131cc81c5.setContent(html_f9dfff8fcacd448da5761ae2d1f1c55d);
        

        marker_f3cbefab8992415daaf670278d70c2bc.bindPopup(popup_46693c85e73b46d0b572461131cc81c5)
        ;

        
    
    
            var marker_1eea27d559144eb7a8a114449f0a2e33 = L.marker(
                [-8.1526, 110.7125],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_13a3afe659964bd48c692da8fa53dc25 = L.popup({"maxWidth": "100%"});

        
            var html_203f1a555fc14038a7aa9f433c4119e0 = $(`<div id="html_203f1a555fc14038a7aa9f433c4119e0" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 GIRISUBO</div>`)[0];
            popup_13a3afe659964bd48c692da8fa53dc25.setContent(html_203f1a555fc14038a7aa9f433c4119e0);
        

        marker_1eea27d559144eb7a8a114449f0a2e33.bindPopup(popup_13a3afe659964bd48c692da8fa53dc25)
        ;

        
    
    
            var marker_4e8d38f5777a4de2a12a7f63daf90634 = L.marker(
                [-7.7764, 110.1136],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_2cf9b0ae94154cc88c72d97d3c8554d9 = L.popup({"maxWidth": "100%"});

        
            var html_294b9d388a584cf997de0696b0918ba3 = $(`<div id="html_294b9d388a584cf997de0696b0918ba3" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 GIRIMULYO</div>`)[0];
            popup_2cf9b0ae94154cc88c72d97d3c8554d9.setContent(html_294b9d388a584cf997de0696b0918ba3);
        

        marker_4e8d38f5777a4de2a12a7f63daf90634.bindPopup(popup_2cf9b0ae94154cc88c72d97d3c8554d9)
        ;

        
    
    
            var marker_f935ab36725f4fc99ded43da80bf4929 = L.marker(
                [-7.8834, 110.5799],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_83591d97a56e4261a715824ff346fadc = L.popup({"maxWidth": "100%"});

        
            var html_42d48e6c878146a9acbcd60e49657fb4 = $(`<div id="html_42d48e6c878146a9acbcd60e49657fb4" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 GEDANGSARI</div>`)[0];
            popup_83591d97a56e4261a715824ff346fadc.setContent(html_42d48e6c878146a9acbcd60e49657fb4);
        

        marker_f935ab36725f4fc99ded43da80bf4929.bindPopup(popup_83591d97a56e4261a715824ff346fadc)
        ;

        
    
    
            var marker_3a23dfb00bf8408c8218e9913c7512f9 = L.marker(
                [-7.7157, 110.3875],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_21afcd1c9dde453885f4c5d1ef1ef65e = L.popup({"maxWidth": "100%"});

        
            var html_0d8b95654d974255b3f0047e7b82eeb4 = $(`<div id="html_0d8b95654d974255b3f0047e7b82eeb4" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 NGAGLIK</div>`)[0];
            popup_21afcd1c9dde453885f4c5d1ef1ef65e.setContent(html_0d8b95654d974255b3f0047e7b82eeb4);
        

        marker_3a23dfb00bf8408c8218e9913c7512f9.bindPopup(popup_21afcd1c9dde453885f4c5d1ef1ef65e)
        ;

        
    
    
            var marker_2b1d60d5328d434dac6296261cc2301c = L.marker(
                [-7.8681, 110.2781],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_e7932654a965487b8446d70a6d76bbc1 = L.popup({"maxWidth": "100%"});

        
            var html_d360ffb51ea74e648aa09998154c4975 = $(`<div id="html_d360ffb51ea74e648aa09998154c4975" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 PAJANGAN</div>`)[0];
            popup_e7932654a965487b8446d70a6d76bbc1.setContent(html_d360ffb51ea74e648aa09998154c4975);
        

        marker_2b1d60d5328d434dac6296261cc2301c.bindPopup(popup_e7932654a965487b8446d70a6d76bbc1)
        ;

        
    
    
            var marker_f85b9d5c4a4841cfbfe9eae9af0e9884 = L.marker(
                [-7.9051, 110.3312],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_799fdabe82274448ad5c316dbc2f5d1b = L.popup({"maxWidth": "100%"});

        
            var html_1b82d7149e83419a9ab40e24ae53cf47 = $(`<div id="html_1b82d7149e83419a9ab40e24ae53cf47" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 BANTUL</div>`)[0];
            popup_799fdabe82274448ad5c316dbc2f5d1b.setContent(html_1b82d7149e83419a9ab40e24ae53cf47);
        

        marker_f85b9d5c4a4841cfbfe9eae9af0e9884.bindPopup(popup_799fdabe82274448ad5c316dbc2f5d1b)
        ;

        
    
    
            var marker_a9702e8ee59d47f9946a51a2e5f9babe = L.marker(
                [-7.7617, 110.2103],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_26edaae09d8346a39ef25848df749064 = L.popup({"maxWidth": "100%"});

        
            var html_87f5f17cea784e519b3269803df09989 = $(`<div id="html_87f5f17cea784e519b3269803df09989" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 NANGGULAN</div>`)[0];
            popup_26edaae09d8346a39ef25848df749064.setContent(html_87f5f17cea784e519b3269803df09989);
        

        marker_a9702e8ee59d47f9946a51a2e5f9babe.bindPopup(popup_26edaae09d8346a39ef25848df749064)
        ;

        
    
    
            var marker_47d8ac157db74ba18edf347bb66bfa14 = L.marker(
                [-7.7533, 110.1363],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_e3cdc7cdd66447aea508a1e59f958cdc = L.popup({"maxWidth": "100%"});

        
            var html_24893d562f6d41758b2bf664fcd2bdc6 = $(`<div id="html_24893d562f6d41758b2bf664fcd2bdc6" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 GIRIMULYO</div>`)[0];
            popup_e3cdc7cdd66447aea508a1e59f958cdc.setContent(html_24893d562f6d41758b2bf664fcd2bdc6);
        

        marker_47d8ac157db74ba18edf347bb66bfa14.bindPopup(popup_e3cdc7cdd66447aea508a1e59f958cdc)
        ;

        
    
    
            var marker_518f7a1e820e4a9ba47b6f43da508304 = L.marker(
                [-7.7526, 110.3952],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_919a4cf2bd9e4d0fa49780554e81ad0d = L.popup({"maxWidth": "100%"});

        
            var html_bd607af3fd0e4b4b99152907ae9c4f24 = $(`<div id="html_bd607af3fd0e4b4b99152907ae9c4f24" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 DEPOK</div>`)[0];
            popup_919a4cf2bd9e4d0fa49780554e81ad0d.setContent(html_bd607af3fd0e4b4b99152907ae9c4f24);
        

        marker_518f7a1e820e4a9ba47b6f43da508304.bindPopup(popup_919a4cf2bd9e4d0fa49780554e81ad0d)
        ;

        
    
    
            var marker_785e8a71dd85449abcdaf220acc640be = L.marker(
                [-7.8249, 110.3757],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_02724b3463ec44299928dde018d016f3 = L.popup({"maxWidth": "100%"});

        
            var html_0885f125ff7843139d2e6977c710fcd6 = $(`<div id="html_0885f125ff7843139d2e6977c710fcd6" style="width: 100.0%; height: 100.0%;">SMP NEGERI 10 YOGYAKARTA</div>`)[0];
            popup_02724b3463ec44299928dde018d016f3.setContent(html_0885f125ff7843139d2e6977c710fcd6);
        

        marker_785e8a71dd85449abcdaf220acc640be.bindPopup(popup_02724b3463ec44299928dde018d016f3)
        ;

        
    
    
            var marker_e2be20d39f3f45ca945c406788c4b757 = L.marker(
                [-7.9671330000000005, 110.265794],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_97dd833b10174cec85fc7858900f3690 = L.popup({"maxWidth": "100%"});

        
            var html_7a8773efeb1e4c3b8890f1717bce3c0f = $(`<div id="html_7a8773efeb1e4c3b8890f1717bce3c0f" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 SANDEN</div>`)[0];
            popup_97dd833b10174cec85fc7858900f3690.setContent(html_7a8773efeb1e4c3b8890f1717bce3c0f);
        

        marker_e2be20d39f3f45ca945c406788c4b757.bindPopup(popup_97dd833b10174cec85fc7858900f3690)
        ;

        
    
    
            var marker_dcfc94cc6d7f47e693393f3023499070 = L.marker(
                [-7.781928, 110.37376499999999],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_29d5bf20ead74201b0712e9e63f02568 = L.popup({"maxWidth": "100%"});

        
            var html_259a3a05e1ed49a1acb869769452f05b = $(`<div id="html_259a3a05e1ed49a1acb869769452f05b" style="width: 100.0%; height: 100.0%;">SMP NEGERI 8 YOGYAKARTA</div>`)[0];
            popup_29d5bf20ead74201b0712e9e63f02568.setContent(html_259a3a05e1ed49a1acb869769452f05b);
        

        marker_dcfc94cc6d7f47e693393f3023499070.bindPopup(popup_29d5bf20ead74201b0712e9e63f02568)
        ;

        
    
    
            var marker_6bb661a668084afd86cdf6f2dd55eb2a = L.marker(
                [-7.8669, 110.4099],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_628c7f3498b6456e8a98820f47080700 = L.popup({"maxWidth": "100%"});

        
            var html_45757956c3b74002a32061576467d1d9 = $(`<div id="html_45757956c3b74002a32061576467d1d9" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 PLERET</div>`)[0];
            popup_628c7f3498b6456e8a98820f47080700.setContent(html_45757956c3b74002a32061576467d1d9);
        

        marker_6bb661a668084afd86cdf6f2dd55eb2a.bindPopup(popup_628c7f3498b6456e8a98820f47080700)
        ;

        
    
    
            var marker_498d811c707a41e9b286e5974316b6f4 = L.marker(
                [-7.8901, 110.3761],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_c33b309cfd9347349985f5f938cbccf1 = L.popup({"maxWidth": "100%"});

        
            var html_516d329df92448c3a20c31f38371846c = $(`<div id="html_516d329df92448c3a20c31f38371846c" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 JETIS</div>`)[0];
            popup_c33b309cfd9347349985f5f938cbccf1.setContent(html_516d329df92448c3a20c31f38371846c);
        

        marker_498d811c707a41e9b286e5974316b6f4.bindPopup(popup_c33b309cfd9347349985f5f938cbccf1)
        ;

        
    
    
            var marker_3c17dd5606e94770a23c535ae5f90692 = L.marker(
                [-7.7957, 110.3646],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_90ba442855504eb8832192d7ff54a060 = L.popup({"maxWidth": "100%"});

        
            var html_13bcbfaba6c1409bb223232bc29fbe54 = $(`<div id="html_13bcbfaba6c1409bb223232bc29fbe54" style="width: 100.0%; height: 100.0%;">SMP NEGERI 3 YOGYAKARTA</div>`)[0];
            popup_90ba442855504eb8832192d7ff54a060.setContent(html_13bcbfaba6c1409bb223232bc29fbe54);
        

        marker_3c17dd5606e94770a23c535ae5f90692.bindPopup(popup_90ba442855504eb8832192d7ff54a060)
        ;

        
    
    
            var marker_d294e39842b24e7baea2a374457e0f40 = L.marker(
                [-7.9239999999999995, 110.2044],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_38cacf0bc35148f7a77f07ceba714f93 = L.popup({"maxWidth": "100%"});

        
            var html_5a5600b7152f49bdacb2ae777f9cb925 = $(`<div id="html_5a5600b7152f49bdacb2ae777f9cb925" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 LENDAH</div>`)[0];
            popup_38cacf0bc35148f7a77f07ceba714f93.setContent(html_5a5600b7152f49bdacb2ae777f9cb925);
        

        marker_d294e39842b24e7baea2a374457e0f40.bindPopup(popup_38cacf0bc35148f7a77f07ceba714f93)
        ;

        
    
    
            var marker_8beb6a818bd94ef6a364043ec7fe5752 = L.marker(
                [-7.7927, 110.3534],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_ba01591e7a9142bfa0882a9b232a0683 = L.popup({"maxWidth": "100%"});

        
            var html_77bab29ed87c40e192f2ef56e27d10e7 = $(`<div id="html_77bab29ed87c40e192f2ef56e27d10e7" style="width: 100.0%; height: 100.0%;">SMP NEGERI 11 YOGYAKARTA</div>`)[0];
            popup_ba01591e7a9142bfa0882a9b232a0683.setContent(html_77bab29ed87c40e192f2ef56e27d10e7);
        

        marker_8beb6a818bd94ef6a364043ec7fe5752.bindPopup(popup_ba01591e7a9142bfa0882a9b232a0683)
        ;

        
    
    
            var marker_044d5d0157544437993ffec47b82d273 = L.marker(
                [-7.9403, 110.2362],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_e67d1eeae5b04a34a47e3b74a8c9fdc2 = L.popup({"maxWidth": "100%"});

        
            var html_9136886e9e174d9c9f43b0ce7e382eed = $(`<div id="html_9136886e9e174d9c9f43b0ce7e382eed" style="width: 100.0%; height: 100.0%;">SMP NEGERI 1 GALUR</div>`)[0];
            popup_e67d1eeae5b04a34a47e3b74a8c9fdc2.setContent(html_9136886e9e174d9c9f43b0ce7e382eed);
        

        marker_044d5d0157544437993ffec47b82d273.bindPopup(popup_e67d1eeae5b04a34a47e3b74a8c9fdc2)
        ;

        
    
    
            var marker_6e76dfd2da2845cbbbc4cd948b9a5f94 = L.marker(
                [-7.9516, 110.2478],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_4a277bf096ee453b80e8faba9b28609b = L.popup({"maxWidth": "100%"});

        
            var html_e1bcb3359c8d4afea2fc7148d933ea0e = $(`<div id="html_e1bcb3359c8d4afea2fc7148d933ea0e" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 SRANDAKAN</div>`)[0];
            popup_4a277bf096ee453b80e8faba9b28609b.setContent(html_e1bcb3359c8d4afea2fc7148d933ea0e);
        

        marker_6e76dfd2da2845cbbbc4cd948b9a5f94.bindPopup(popup_4a277bf096ee453b80e8faba9b28609b)
        ;

        
    
    
            var marker_72da98889eb24fabb51e360d26904473 = L.marker(
                [-8.0334, 110.4658],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_51c05710120c469896a34a36ac3098f3 = L.popup({"maxWidth": "100%"});

        
            var html_f2e0bec2897a4fcaabc6d2446144abb9 = $(`<div id="html_f2e0bec2897a4fcaabc6d2446144abb9" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 PANGGANG</div>`)[0];
            popup_51c05710120c469896a34a36ac3098f3.setContent(html_f2e0bec2897a4fcaabc6d2446144abb9);
        

        marker_72da98889eb24fabb51e360d26904473.bindPopup(popup_51c05710120c469896a34a36ac3098f3)
        ;

        
    
    
            var marker_521a4255d2d041d5a7b544ffeebfd6d1 = L.marker(
                [-7.7736, 110.4119],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_215319d7d5ac46428fae5fdd54172b31 = L.popup({"maxWidth": "100%"});

        
            var html_7e9961357bb14dafa7d0e9979567059e = $(`<div id="html_7e9961357bb14dafa7d0e9979567059e" style="width: 100.0%; height: 100.0%;">SMP NEGERI 4 DEPOK</div>`)[0];
            popup_215319d7d5ac46428fae5fdd54172b31.setContent(html_7e9961357bb14dafa7d0e9979567059e);
        

        marker_521a4255d2d041d5a7b544ffeebfd6d1.bindPopup(popup_215319d7d5ac46428fae5fdd54172b31)
        ;

        
    
    
            var marker_3208c1dbcf7e400e9399dac828221e4d = L.marker(
                [-7.875141999999999, 110.336294],
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        var popup_b1d30fd5f8c94b23b4cb301ef3e21193 = L.popup({"maxWidth": "100%"});

        
            var html_b423dad01bb247038780b34a9bebcfa9 = $(`<div id="html_b423dad01bb247038780b34a9bebcfa9" style="width: 100.0%; height: 100.0%;">SMP NEGERI 2 BANTUL</div>`)[0];
            popup_b1d30fd5f8c94b23b4cb301ef3e21193.setContent(html_b423dad01bb247038780b34a9bebcfa9);
        

        marker_3208c1dbcf7e400e9399dac828221e4d.bindPopup(popup_b1d30fd5f8c94b23b4cb301ef3e21193)
        ;

        
    
    
            var choropleth_d64366794c8b4aa08d6819eba57319e4 = L.featureGroup(
                {}
            ).addTo(map_5e76493185984f9cbfb9a9690f6cded8);
        
    
        function geo_json_5d752fa3f6e34edbac4a4546282329a3_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "black", "fillColor": "BuPu", "fillOpacity": 0.01, "opacity": 0.25, "weight": 1};
            }
        }
        function geo_json_5d752fa3f6e34edbac4a4546282329a3_onEachFeature(feature, layer) {
            layer.on({
                click: function(e) {
                    map_5e76493185984f9cbfb9a9690f6cded8.fitBounds(e.target.getBounds());
                }
            });
        };
        var geo_json_5d752fa3f6e34edbac4a4546282329a3 = L.geoJson(null, {
                onEachFeature: geo_json_5d752fa3f6e34edbac4a4546282329a3_onEachFeature,
            
                style: geo_json_5d752fa3f6e34edbac4a4546282329a3_styler,
        }).addTo(choropleth_d64366794c8b4aa08d6819eba57319e4);
            geo_json_5d752fa3f6e34edbac4a4546282329a3.addData({"features": [{"geometry": {"coordinates": [[[110.13772168861348, -7.653535631293568]]], "type": "Polygon"}, "id": "0", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.15775693935268, -7.6864506860793895], [110.13772168861348, -7.653535631293568], [110.11883948544927, -7.7141574414523575], [110.15145763454318, -7.713455531914894]]], "type": "Polygon"}, "id": "1", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.72994575675196, -7.876649586312864], [110.73521994409441, -7.838918861478393], [110.78347447596468, -7.868303710736696]]], "type": "Polygon"}, "id": "2", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.75384877750611, -8.117492787286066], [110.72316604844815, -8.075900643451941], [110.68734792824492, -8.132493273373022], [110.74136077950709, -8.135696191776692]]], "type": "Polygon"}, "id": "3", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.75384877750611, -8.117492787286066], [110.83259343541447, -8.110770682342658], [110.73956642002317, -8.282577332389637], [110.74136077950709, -8.135696191776692]]], "type": "Polygon"}, "id": "4", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.60852623747695, -8.050313305935438], [110.60453106715477, -8.062365775063851], [110.58386636919298, -8.094803587800689], [110.56002000530974, -8.089055418941012], [110.5634812067252, -8.037144159283121], [110.60717113024593, -8.049073677407575]]], "type": "Polygon"}, "id": "5", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.56002000530974, -8.089055418941012], [110.5532694774723, -8.090830814320663], [110.46463044354836, -8.248355040322691], [109.94655001946765, -9.573111024046028]]], "type": "Polygon"}, "id": "6", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.5121096194955, -8.074264728516463], [110.46463044354836, -8.248355040322691], [109.94655001946765, -9.573111024046028], [110.46185745782972, -8.063399501925884], [110.48580713970372, -8.053523344452074]]], "type": "Polygon"}, "id": "7", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.52519965010252, -8.0694216939367], [110.5532694774723, -8.090830814320663], [110.56002000530974, -8.089055418941012], [110.5634812067252, -8.037144159283121], [110.54931212287943, -8.027633083742254]]], "type": "Polygon"}, "id": "8", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.52519965010252, -8.0694216939367], [110.5532694774723, -8.090830814320663], [110.46463044354836, -8.248355040322691], [110.5121096194955, -8.074264728516463]]], "type": "Polygon"}, "id": "9", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.23606037775201, -7.493366688207678], [110.21635233016646, -7.626017008494996], [110.15775693935268, -7.6864506860793895], [110.13772168861348, -7.653535631293568]]], "type": "Polygon"}, "id": "10", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.64931410605352, -8.081988473517084], [110.638498853211, -8.131244896788953], [110.63722931197985, -8.167109436569067], [110.6733034650727, -8.138288973146583], [110.68421572661074, -8.068571746653532]]], "type": "Polygon"}, "id": "11", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.638498853211, -8.131244896788953], [110.60453106715477, -8.062365775063851], [110.58386636919298, -8.094803587800689], [110.61914824992589, -8.198759129245868], [110.63722931197985, -8.167109436569067]]], "type": "Polygon"}, "id": "12", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.6733034650727, -8.138288973146583], [110.68734792824492, -8.132493273373022], [110.74136077950709, -8.135696191776692], [110.73956642002317, -8.282577332389637], [107.90037946373589, -18.203030579651482], [110.61914824992589, -8.198759129245868], [110.63722931197985, -8.167109436569067]]], "type": "Polygon"}, "id": "13", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.64931410605352, -8.081988473517084], [110.61493879080389, -8.050194239958547], [110.60852623747695, -8.050313305935438], [110.60453106715477, -8.062365775063851], [110.638498853211, -8.131244896788953]]], "type": "Polygon"}, "id": "14", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.68421572661074, -8.068571746653532], [110.70382373893084, -8.050966452931453], [110.71861972728937, -8.060205010879951], [110.72316604844815, -8.075900643451941], [110.68734792824492, -8.132493273373022], [110.6733034650727, -8.138288973146583]]], "type": "Polygon"}, "id": "15", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.13385526957153, -7.794969039620599], [110.13841003414953, -7.778076959965125], [110.07742730646977, -7.718150210253843], [109.97101086483292, -7.702904008519336], [110.07260836093522, -7.786697752923714]]], "type": "Polygon"}, "id": "16", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.09122737736574, -7.820716610046757], [110.0759167581022, -7.854779770733856]]], "type": "Polygon"}, "id": "17", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.13660140345047, -7.828096090439126], [110.13803542555762, -7.806623496255741], [110.13385526957153, -7.794969039620599], [110.07260836093522, -7.786697752923714], [110.09122737736574, -7.820716610046757], [110.1316037662451, -7.832959013671992]]], "type": "Polygon"}, "id": "18", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.66470228179571, -7.8290379472723455], [110.73675899070066, -7.760433056758048], [110.72885455840456, -7.808677350427352], [110.69024786228194, -7.836385505539284]]], "type": "Polygon"}, "id": "19", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.70027385620915, -7.8626758896150974], [110.73354180327868, -7.836800819672139], [110.72885455840456, -7.808677350427352], [110.69024786228194, -7.836385505539284]]], "type": "Polygon"}, "id": "20", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.66470228179571, -7.8290379472723455], [110.73675899070066, -7.760433056758048], [110.87913887039227, -7.3242374536039305], [110.65427905501802, -7.603305002471506], [110.65373491384845, -7.830756011349922]]], "type": "Polygon"}, "id": "21", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.49718600844382, -7.953334594886424], [110.50908332210088, -7.957121864016178], [110.55096501165362, -7.989033266770934], [110.5464309640643, -8.02126013245266], [110.49351657901815, -8.026340432498984], [110.48470196015231, -8.014031893003557], [110.48840854100538, -7.95719636679338]]], "type": "Polygon"}, "id": "22", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.5464309640643, -8.02126013245266], [110.54931212287943, -8.027633083742254], [110.52519965010252, -8.0694216939367], [110.5121096194955, -8.074264728516463], [110.48580713970372, -8.053523344452074], [110.49351657901815, -8.026340432498984]]], "type": "Polygon"}, "id": "23", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.5464309640643, -8.02126013245266], [110.54931212287943, -8.027633083742254], [110.5634812067252, -8.037144159283121], [110.60717113024593, -8.049073677407575], [110.60552012250388, -7.993239597403736], [110.56280618146644, -7.982999322122624], [110.55096501165362, -7.989033266770934]]], "type": "Polygon"}, "id": "24", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.49718600844382, -7.953334594886424], [110.5038108559025, -7.903638063279117], [110.48768879217178, -7.882924159921039], [110.45178543424488, -7.877414096673725], [110.438749715804, -7.902928848070472], [110.46809130147984, -7.955555270085402], [110.48840854100538, -7.95719636679338]]], "type": "Polygon"}, "id": "25", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.46863310907538, -7.673207113167895], [110.44250681730406, -7.674543041266746], [110.441493788377, -7.673239549034347], [110.43104575801699, -7.650840471376672], [110.44077257488252, -7.634091152760917], [110.50133056868765, -7.660977707200779]]], "type": "Polygon"}, "id": "26", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.44250681730406, -7.674543041266746], [110.42587162606037, -7.690404941307507], [110.41329227466518, -7.685072154773009], [110.41573302407663, -7.662991886841568], [110.441493788377, -7.673239549034347]]], "type": "Polygon"}, "id": "27", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.43104575801699, -7.650840471376672], [110.40301527979307, -7.645375158636503], [110.42320664220476, -7.596386589336047], [110.44077257488252, -7.634091152760917]]], "type": "Polygon"}, "id": "28", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.50133056868765, -7.660977707200779], [110.6120700507931, -7.6457818573585605], [110.65427905501802, -7.603305002471506], [110.87913887039227, -7.3242374536039305]]], "type": "Polygon"}, "id": "29", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.39740214496368, -7.708482933021196], [110.39113795679062, -7.701687237972853], [110.40351952817532, -7.682901405527089], [110.41329227466518, -7.685072154773009], [110.42587162606037, -7.690404941307507], [110.42583400694595, -7.705791159105697]]], "type": "Polygon"}, "id": "30", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.35678236240928, -7.698315951794214], [110.37360505022829, -7.680521550825608], [110.38600367666373, -7.701632423594275], [110.37309709175318, -7.711396911243172], [110.35653727566213, -7.699518896625509]]], "type": "Polygon"}, "id": "31", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.39117285058394, -7.666814759480366], [110.40351952817532, -7.682901405527089], [110.39113795679062, -7.701687237972853], [110.38600367666373, -7.701632423594275], [110.37360505022829, -7.680521550825608], [110.37531000668008, -7.671160062515322]]], "type": "Polygon"}, "id": "32", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.40152420792062, -7.646687173852344], [110.40301527979307, -7.645375158636503], [110.42320664220476, -7.596386589336047]]], "type": "Polygon"}, "id": "33", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.4013147675145, -7.647706020164679], [110.41573302407663, -7.662991886841568], [110.41329227466518, -7.685072154773009], [110.40351952817532, -7.682901405527089], [110.39117285058394, -7.666814759480366]]], "type": "Polygon"}, "id": "34", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.4013147675145, -7.647706020164679], [110.41573302407663, -7.662991886841568], [110.441493788377, -7.673239549034347], [110.43104575801699, -7.650840471376672], [110.40301527979307, -7.645375158636503], [110.40152420792062, -7.646687173852344]]], "type": "Polygon"}, "id": "35", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.31139583663416, -7.692910379979076], [110.28732305834068, -7.6773428921062825], [110.2442079818276, -7.512043596474774], [110.30437296577587, -7.609143507286237], [110.32188315032928, -7.6765580282444565]]], "type": "Polygon"}, "id": "36", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.54810290629496, -7.929816168215118], [110.50908332210088, -7.957121864016178], [110.55096501165362, -7.989033266770934], [110.56280618146644, -7.982999322122624], [110.57622957905988, -7.954939468733485], [110.57508204611553, -7.944385582097419]]], "type": "Polygon"}, "id": "37", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.44836259323505, -7.721005490026009], [110.46863310907538, -7.673207113167895], [110.50133056868765, -7.660977707200779], [110.6120700507931, -7.6457818573585605], [110.59049800935796, -7.683381409287651]]], "type": "Polygon"}, "id": "38", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.44836259323505, -7.721005490026009], [110.46863310907538, -7.673207113167895], [110.44250681730406, -7.674543041266746], [110.42587162606037, -7.690404941307507], [110.42583400694595, -7.705791159105697], [110.43595228079708, -7.72946069257888], [110.43953715204388, -7.729303514412916]]], "type": "Polygon"}, "id": "39", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.51191849957597, -7.851824089485042], [110.53369107397178, -7.8941041822042415], [110.5038108559025, -7.903638063279117], [110.48768879217178, -7.882924159921039], [110.50470775919894, -7.850500286026968]]], "type": "Polygon"}, "id": "40", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.09620800301363, -7.86893853436404], [110.08643585318143, -7.948111748293136]]], "type": "Polygon"}, "id": "41", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[]], "type": "Polygon"}, "id": "42", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.08086491216095, -7.860626250380652], [110.0759167581022, -7.854779770733856]]], "type": "Polygon"}, "id": "43", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.26749391320115, -7.700941317661205], [110.2196449074782, -7.704974567185748], [110.22124017306356, -7.6648728909194], [110.27353464503356, -7.688568823530841]]], "type": "Polygon"}, "id": "44", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.2196449074782, -7.704974567185748], [110.21623153742973, -7.713814018587119], [110.15714981945786, -7.717469576388063], [110.15145763454318, -7.713455531914894], [110.15775693935268, -7.6864506860793895], [110.21635233016646, -7.626017008494996], [110.22124017306356, -7.6648728909194]]], "type": "Polygon"}, "id": "45", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.27353464503356, -7.688568823530841], [110.28732305834068, -7.6773428921062825], [110.2442079818276, -7.512043596474774], [110.23606037775201, -7.493366688207678], [110.21635233016646, -7.626017008494996], [110.22124017306356, -7.6648728909194]]], "type": "Polygon"}, "id": "46", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.1604925464527, -7.763026309121625], [110.18301494112806, -7.795277312147876], [110.19227060402005, -7.799680261758897], [110.19401176982078, -7.799231540263973], [110.20151880903055, -7.776429785654859], [110.19462360224938, -7.759749952108021], [110.16301441631505, -7.756541500904155]]], "type": "Polygon"}, "id": "47", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.1604925464527, -7.763026309121625], [110.13841003414953, -7.778076959965125], [110.13385526957153, -7.794969039620599], [110.13803542555762, -7.806623496255741], [110.18301494112806, -7.795277312147876]]], "type": "Polygon"}, "id": "48", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.16301441631505, -7.756541500904155], [110.15714981945786, -7.717469576388063], [110.21623153742973, -7.713814018587119], [110.2203811056418, -7.723433472169635], [110.19462360224938, -7.759749952108021]]], "type": "Polygon"}, "id": "49", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.1604925464527, -7.763026309121625], [110.13841003414953, -7.778076959965125], [110.07742730646977, -7.718150210253843], [110.11883948544927, -7.7141574414523575], [110.15145763454318, -7.713455531914894], [110.15714981945786, -7.717469576388063], [110.16301441631505, -7.756541500904155]]], "type": "Polygon"}, "id": "50", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.34715975877955, -7.668441012935287], [110.36924751021436, -7.6673381928196465], [110.36558912633419, -7.642210209763069], [110.34075194118336, -7.649036879042037], [110.3439214042174, -7.666563123270917]]], "type": "Polygon"}, "id": "51", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.36558912633419, -7.642210209763069], [110.37151118864985, -7.630994556317889], [110.40152420792062, -7.646687173852344], [110.4013147675145, -7.647706020164679], [110.39117285058394, -7.666814759480366], [110.37531000668008, -7.671160062515322], [110.36924751021436, -7.6673381928196465]]], "type": "Polygon"}, "id": "52", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.34715975877955, -7.668441012935287], [110.3483865687974, -7.6826477702680736], [110.35678236240928, -7.698315951794214], [110.37360505022829, -7.680521550825608], [110.37531000668008, -7.671160062515322], [110.36924751021436, -7.6673381928196465]]], "type": "Polygon"}, "id": "53", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.34075194118336, -7.649036879042037], [110.30437296577587, -7.609143507286237], [110.2442079818276, -7.512043596474774], [110.23606037775201, -7.493366688207678], [110.17680039491958, -6.9997261736504335], [110.37151118864985, -7.630994556317889], [110.36558912633419, -7.642210209763069]]], "type": "Polygon"}, "id": "54", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.3439214042174, -7.666563123270917], [110.32188315032928, -7.6765580282444565], [110.30437296577587, -7.609143507286237], [110.34075194118336, -7.649036879042037]]], "type": "Polygon"}, "id": "55", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.54316328108607, -7.888967801648159], [110.55813952480217, -7.890043755562689], [110.58029617747192, -7.907716693298431], [110.54894098132553, -7.925135496085984], [110.53767234296724, -7.893183298367254]]], "type": "Polygon"}, "id": "56", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.54894098132553, -7.925135496085984], [110.54810290629496, -7.929816168215118], [110.57508204611553, -7.944385582097419], [110.58928117383067, -7.912689465962648], [110.58645328802614, -7.910134093346274], [110.58029617747192, -7.907716693298431]]], "type": "Polygon"}, "id": "57", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.53767234296724, -7.893183298367254], [110.53369107397178, -7.8941041822042415], [110.5038108559025, -7.903638063279117], [110.49718600844382, -7.953334594886424], [110.50908332210088, -7.957121864016178], [110.54810290629496, -7.929816168215118], [110.54894098132553, -7.925135496085984]]], "type": "Polygon"}, "id": "58", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.54316328108607, -7.888967801648159], [110.54066657235633, -7.85420552670927], [110.51191849957597, -7.851824089485042], [110.53369107397178, -7.8941041822042415], [110.53767234296724, -7.893183298367254]]], "type": "Polygon"}, "id": "59", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[111.06650230637493, -7.962693918093164], [110.83259343541447, -8.110770682342658], [110.75384877750611, -8.117492787286066], [110.72316604844815, -8.075900643451941], [110.71861972728937, -8.060205010879951], [110.97169492307377, -7.97502759870658]]], "type": "Polygon"}, "id": "60", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[111.11397357405205, -7.946656575059937]]], "type": "Polygon"}, "id": "61", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[111.06650230637493, -7.962693918093164], [110.83259343541447, -8.110770682342658], [110.73956642002317, -8.282577332389637], [107.90037946373589, -18.203030579651482]]], "type": "Polygon"}, "id": "62", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.46877870618502, -7.780351575731593], [110.47369527027027, -7.797748648648646], [110.49474405594405, -7.803762587412588], [110.49445141756324, -7.779766240186098], [110.48177513554845, -7.77211546642569]]], "type": "Polygon"}, "id": "63", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.49445141756324, -7.779766240186098], [110.57782840924172, -7.707439211260216], [110.50338655810984, -7.813201109514687], [110.49474405594405, -7.803762587412588]]], "type": "Polygon"}, "id": "64", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.61267498264873, -7.856096504256446], [110.62231192504454, -7.834097019595302], [110.58183549508867, -7.7918960299671305], [110.56101643177519, -7.821253787450662], [110.55950664117181, -7.834272992784437], [110.58052641940078, -7.861954029529223], [110.59188624273358, -7.865191579179071], [110.60369587666747, -7.86299091312123]]], "type": "Polygon"}, "id": "65", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.56101643177519, -7.821253787450662], [110.50395074061423, -7.815477988907391], [110.50338655810984, -7.813201109514687], [110.57782840924172, -7.707439211260216], [110.58498950681656, -7.699258199788368], [110.58183549508867, -7.7918960299671305]]], "type": "Polygon"}, "id": "66", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.58052641940078, -7.861954029529223], [110.55813952480217, -7.890043755562689], [110.54316328108607, -7.888967801648159], [110.54066657235633, -7.85420552670927], [110.55950664117181, -7.834272992784437]]], "type": "Polygon"}, "id": "67", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.60369587666747, -7.86299091312123], [110.61802559979047, -7.913797687585772], [110.58928117383067, -7.912689465962648], [110.58645328802614, -7.910134093346274], [110.59188624273358, -7.865191579179071]]], "type": "Polygon"}, "id": "68", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.58052641940078, -7.861954029529223], [110.55813952480217, -7.890043755562689], [110.58029617747192, -7.907716693298431], [110.58645328802614, -7.910134093346274], [110.59188624273358, -7.865191579179071]]], "type": "Polygon"}, "id": "69", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.482032148963, -7.754038856269537], [110.46395348114639, -7.751993459545759], [110.45306919023137, -7.737612660668388], [110.55440983281099, -7.707006426332212]]], "type": "Polygon"}, "id": "70", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.55440983281099, -7.707006426332212], [110.58751966044095, -7.689518841316383], [110.59049800935796, -7.683381409287651], [110.44836259323505, -7.721005490026009], [110.43953715204388, -7.729303514412916], [110.45306919023137, -7.737612660668388]]], "type": "Polygon"}, "id": "71", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.46395348114639, -7.751993459545759], [110.45604909841148, -7.773852493281813], [110.44085906686816, -7.778772534945221], [110.43483301911495, -7.730564152919619], [110.43595228079708, -7.72946069257888], [110.43953715204388, -7.729303514412916], [110.45306919023137, -7.737612660668388]]], "type": "Polygon"}, "id": "72", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.482032148963, -7.754038856269537], [110.48177513554845, -7.77211546642569], [110.46877870618502, -7.780351575731593], [110.45604909841148, -7.773852493281813], [110.46395348114639, -7.751993459545759]]], "type": "Polygon"}, "id": "73", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.482032148963, -7.754038856269537], [110.48177513554845, -7.77211546642569], [110.49445141756324, -7.779766240186098], [110.57782840924172, -7.707439211260216], [110.58498950681656, -7.699258199788368], [110.58751966044095, -7.689518841316383], [110.55440983281099, -7.707006426332212]]], "type": "Polygon"}, "id": "74", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.4371874256429, -7.782683084332388], [110.44085906686816, -7.778772534945221], [110.45604909841148, -7.773852493281813], [110.46877870618502, -7.780351575731593], [110.47369527027027, -7.797748648648646], [110.46018015654442, -7.805995158718659]]], "type": "Polygon"}, "id": "75", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.4991071929627, -7.831715200282154], [110.50470775919894, -7.850500286026968], [110.51191849957597, -7.851824089485042], [110.54066657235633, -7.85420552670927], [110.55950664117181, -7.834272992784437], [110.56101643177519, -7.821253787450662], [110.50395074061423, -7.815477988907391], [110.49899610209668, -7.827448873963716]]], "type": "Polygon"}, "id": "76", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.41472104516434, -7.951353249273225], [110.40465437914476, -7.930358598216327], [110.41058664779524, -7.911902651303725], [110.438749715804, -7.902928848070472], [110.46809130147984, -7.955555270085402], [110.45856802264535, -7.960165632002253]]], "type": "Polygon"}, "id": "77", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.38731903423302, -7.989542477177513], [110.3802573554643, -7.988175121741584], [110.37194063656591, -7.980585346831924], [110.38827402257485, -7.934501864878128], [110.40465437914476, -7.930358598216327], [110.41472104516434, -7.951353249273225]]], "type": "Polygon"}, "id": "78", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.33553483628344, -7.981277271505711], [110.31798205266159, -7.96338259661529], [110.29843115453792, -7.970957561618291], [110.2979013452813, -7.9872858925216805], [110.33190278146844, -7.98599218377355]]], "type": "Polygon"}, "id": "79", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.31798205266159, -7.96338259661529], [110.31844175268664, -7.957270618725235], [110.30064942869699, -7.929840785907855], [110.28476716721285, -7.956400952005641], [110.29843115453792, -7.970957561618291]]], "type": "Polygon"}, "id": "80", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.33553483628344, -7.981277271505711], [110.35975344135032, -7.974023762515539], [110.35270272636808, -7.949183651337331], [110.34169929582798, -7.942793339447131], [110.31844175268664, -7.957270618725235], [110.31798205266159, -7.96338259661529]]], "type": "Polygon"}, "id": "81", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.33553483628344, -7.981277271505711], [110.35975344135032, -7.974023762515539], [110.37194063656591, -7.980585346831924], [110.3802573554643, -7.988175121741584], [110.31439621295664, -8.076067560594417], [110.33190278146844, -7.98599218377355]]], "type": "Polygon"}, "id": "82", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.28242111116332, -7.956925070910322], [110.14597526670869, -8.219097802793387], [110.08320438086574, -8.322831889639001], [110.1193193736731, -8.212461193556356], [110.21105693862646, -8.012353473820605], [110.26414268197975, -7.950856991112889]]], "type": "Polygon"}, "id": "83", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.1193193736731, -8.212461193556356], [110.17638840747315, -7.941836328734491], [110.17528970492279, -7.9258502066265555], [110.15378595313733, -7.911562478930173], [110.12733356859474, -7.911237032506488], [110.08643585318143, -7.948111748293136]]], "type": "Polygon"}, "id": "84", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.14597526670869, -8.219097802793387], [110.2979013452813, -7.9872858925216805], [110.33190278146844, -7.98599218377355], [110.31439621295664, -8.076067560594417], [110.16240472313888, -8.398048155911845], [109.7806479397015, -9.067008257084169], [110.08320438086574, -8.322831889639001]]], "type": "Polygon"}, "id": "85", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.28242111116332, -7.956925070910322], [110.28476716721285, -7.956400952005641], [110.29843115453792, -7.970957561618291], [110.2979013452813, -7.9872858925216805], [110.14597526670869, -8.219097802793387]]], "type": "Polygon"}, "id": "86", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.28242111116332, -7.956925070910322], [110.28476716721285, -7.956400952005641], [110.30064942869699, -7.929840785907855], [110.30067080282757, -7.929660418244555], [110.29944098805167, -7.928168698470084], [110.2801510853724, -7.9156900552274285], [110.2646889037433, -7.918178222386134], [110.26158336546541, -7.945378454199413], [110.26414268197975, -7.950856991112889]]], "type": "Polygon"}, "id": "87", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.15921353459163, -7.879241812176223], [110.15378595313733, -7.911562478930173], [110.12733356859474, -7.911237032506488], [110.13045611340114, -7.885968914785161]]], "type": "Polygon"}, "id": "88", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.11480601506184, -7.863767942199554], [110.09620800301363, -7.86893853436404], [110.08643585318143, -7.948111748293136], [110.12733356859474, -7.911237032506488], [110.13045611340114, -7.885968914785161]]], "type": "Polygon"}, "id": "89", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.12915023577854, -7.842990844892911], [110.1316037662451, -7.832959013671992], [110.09122737736574, -7.820716610046757], [110.0759167581022, -7.854779770733856], [110.08086491216095, -7.860626250380652], [110.09620800301363, -7.86893853436404], [110.11480601506184, -7.863767942199554]]], "type": "Polygon"}, "id": "90", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.22385015086422, -7.96458170353761], [110.22238467063127, -7.928082973860471], [110.23303617809735, -7.9073027323008995], [110.24465720007815, -7.9432222547870275]]], "type": "Polygon"}, "id": "91", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.24465720007815, -7.9432222547870275], [110.26158336546541, -7.945378454199413], [110.2646889037433, -7.918178222386134], [110.2338490461643, -7.9042015381631305], [110.23303617809735, -7.9073027323008995]]], "type": "Polygon"}, "id": "92", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.22385015086422, -7.96458170353761], [110.21105693862646, -8.012353473820605], [110.1193193736731, -8.212461193556356], [110.17638840747315, -7.941836328734491], [110.22238467063127, -7.928082973860471]]], "type": "Polygon"}, "id": "93", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.22385015086422, -7.96458170353761], [110.21105693862646, -8.012353473820605], [110.26414268197975, -7.950856991112889], [110.26158336546541, -7.945378454199413], [110.24465720007815, -7.9432222547870275]]], "type": "Polygon"}, "id": "94", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.2249776498726, -7.893938230363448], [110.23119996711475, -7.898312644666236], [110.2338490461643, -7.9042015381631305], [110.23303617809735, -7.9073027323008995], [110.22238467063127, -7.928082973860471], [110.17638840747315, -7.941836328734491], [110.17528970492279, -7.9258502066265555], [110.1934116961013, -7.898877940686439]]], "type": "Polygon"}, "id": "95", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.3336213618011, -7.718806140127597], [110.30110684048874, -7.743106466582094], [110.28132866624841, -7.7342662220352745], [110.28217424914841, -7.728957245853018], [110.3116758427114, -7.693766534148956], [110.31911837015684, -7.699577827677675], [110.33300327859591, -7.714173926451192]]], "type": "Polygon"}, "id": "96", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.3116758427114, -7.693766534148956], [110.31139583663416, -7.692910379979076], [110.28732305834068, -7.6773428921062825], [110.27353464503356, -7.688568823530841], [110.26749391320115, -7.700941317661205], [110.28217424914841, -7.728957245853018]]], "type": "Polygon"}, "id": "97", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.31911837015684, -7.699577827677675], [110.3483865687974, -7.6826477702680736], [110.34715975877955, -7.668441012935287], [110.3439214042174, -7.666563123270917], [110.32188315032928, -7.6765580282444565], [110.31139583663416, -7.692910379979076], [110.3116758427114, -7.693766534148956]]], "type": "Polygon"}, "id": "98", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.33300327859591, -7.714173926451192], [110.35653727566213, -7.699518896625509], [110.35678236240928, -7.698315951794214], [110.3483865687974, -7.6826477702680736], [110.31911837015684, -7.699577827677675]]], "type": "Polygon"}, "id": "99", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.3271016271767, -7.75566468741079], [110.33539794103234, -7.721294244294581], [110.3336213618011, -7.718806140127597], [110.30110684048874, -7.743106466582094], [110.30408414020805, -7.74771694527363]]], "type": "Polygon"}, "id": "100", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.618276763682, -7.947381086912382], [110.62046733272165, -7.914702163282808], [110.61802559979047, -7.913797687585772], [110.58928117383067, -7.912689465962648], [110.57508204611553, -7.944385582097419], [110.57622957905988, -7.954939468733485], [110.5974014918859, -7.953739937908542]]], "type": "Polygon"}, "id": "101", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.60998786830142, -7.990659770737461], [110.60552012250388, -7.993239597403736], [110.56280618146644, -7.982999322122624], [110.57622957905988, -7.954939468733485], [110.5974014918859, -7.953739937908542]]], "type": "Polygon"}, "id": "102", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.6261812996696, -7.983775694592201], [110.60998786830142, -7.990659770737461], [110.60552012250388, -7.993239597403736], [110.60717113024593, -8.049073677407575], [110.60852623747695, -8.050313305935438], [110.61493879080389, -8.050194239958547], [110.64710223624058, -8.03031011425474]]], "type": "Polygon"}, "id": "103", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.6927139804811, -8.026535903023571], [110.70382373893084, -8.050966452931453], [110.68421572661074, -8.068571746653532], [110.64931410605352, -8.081988473517084], [110.61493879080389, -8.050194239958547], [110.64710223624058, -8.03031011425474]]], "type": "Polygon"}, "id": "104", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.63447923876201, -7.973812105985726], [110.618276763682, -7.947381086912382], [110.5974014918859, -7.953739937908542], [110.60998786830142, -7.990659770737461], [110.6261812996696, -7.983775694592201]]], "type": "Polygon"}, "id": "105", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.6495743095893, -7.905122151686519], [110.62046733272165, -7.914702163282808], [110.618276763682, -7.947381086912382], [110.63447923876201, -7.973812105985726], [110.6518158521254, -7.971353697871646], [110.6633777389081, -7.927265031942042]]], "type": "Polygon"}, "id": "106", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.7132026558511, -7.893629617886849], [110.72994575675196, -7.876649586312864], [110.73521994409441, -7.838918861478393], [110.73354180327868, -7.836800819672139], [110.70027385620915, -7.8626758896150974], [110.69457356402387, -7.880953016939324]]], "type": "Polygon"}, "id": "107", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.71480389908257, -7.896669266055047], [110.7281666860465, -7.905577790697677], [110.89676314680254, -7.9063565272369365], [110.78347447596468, -7.868303710736696], [110.72994575675196, -7.876649586312864], [110.7132026558511, -7.893629617886849]]], "type": "Polygon"}, "id": "108", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.67652556728926, -7.985062752165773], [110.70184447930178, -7.951388744206639], [110.73001790957818, -7.955055946907903], [110.75437646658987, -7.9726236334799765], [110.69303325010397, -8.024667878273647]]], "type": "Polygon"}, "id": "109", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.73001790957818, -7.955055946907903], [110.7281666860465, -7.905577790697677], [110.89676314680254, -7.9063565272369365], [111.11397357405205, -7.946656575059937], [111.06650230637493, -7.962693918093164], [110.97169492307377, -7.97502759870658], [110.75437646658987, -7.9726236334799765]]], "type": "Polygon"}, "id": "110", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.69303325010397, -8.024667878273647], [110.6927139804811, -8.026535903023571], [110.70382373893084, -8.050966452931453], [110.71861972728937, -8.060205010879951], [110.97169492307377, -7.97502759870658], [110.75437646658987, -7.9726236334799765]]], "type": "Polygon"}, "id": "111", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.70184447930178, -7.951388744206639], [110.69242191824114, -7.936325930096226], [110.71480389908257, -7.896669266055047], [110.7281666860465, -7.905577790697677], [110.73001790957818, -7.955055946907903]]], "type": "Polygon"}, "id": "112", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.67652556728926, -7.985062752165773], [110.6518158521254, -7.971353697871646], [110.6633777389081, -7.927265031942042], [110.69242191824114, -7.936325930096226], [110.70184447930178, -7.951388744206639]]], "type": "Polygon"}, "id": "113", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.67652556728926, -7.985062752165773], [110.6518158521254, -7.971353697871646], [110.63447923876201, -7.973812105985726], [110.6261812996696, -7.983775694592201], [110.64710223624058, -8.03031011425474], [110.6927139804811, -8.026535903023571], [110.69303325010397, -8.024667878273647]]], "type": "Polygon"}, "id": "114", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.46016105258357, -7.851346811747089], [110.4991071929627, -7.831715200282154], [110.50470775919894, -7.850500286026968], [110.48768879217178, -7.882924159921039], [110.45178543424488, -7.877414096673725], [110.45060708403653, -7.875122737395989], [110.45119534975376, -7.86843337765223]]], "type": "Polygon"}, "id": "115", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.46226968497625, -7.824926888238714], [110.49899610209668, -7.827448873963716], [110.4991071929627, -7.831715200282154], [110.46016105258357, -7.851346811747089]]], "type": "Polygon"}, "id": "116", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.46226968497625, -7.824926888238714], [110.49899610209668, -7.827448873963716], [110.50395074061423, -7.815477988907391], [110.50338655810984, -7.813201109514687], [110.49474405594405, -7.803762587412588], [110.47369527027027, -7.797748648648646], [110.46018015654442, -7.805995158718659], [110.45621172886702, -7.8185043329191934]]], "type": "Polygon"}, "id": "117", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.35657686183615, -7.944345898417821], [110.35270272636808, -7.949183651337331], [110.35975344135032, -7.974023762515539], [110.37194063656591, -7.980585346831924], [110.38827402257485, -7.934501864878128], [110.37430744899358, -7.930961043406819]]], "type": "Polygon"}, "id": "118", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.3658394943125, -7.907039071432785], [110.39745742694953, -7.899873856482655], [110.41058664779524, -7.911902651303725], [110.40465437914476, -7.930358598216327], [110.38827402257485, -7.934501864878128], [110.37430744899358, -7.930961043406819]]], "type": "Polygon"}, "id": "119", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.44440557137034, -8.018522399671339], [110.43595227237859, -7.996100539540755], [110.39074344495145, -7.992522862550108], [110.40357488926797, -8.045447776741923], [110.4378526127034, -8.036033978481873]]], "type": "Polygon"}, "id": "120", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.39074344495145, -7.992522862550108], [110.38731903423302, -7.989542477177513], [110.41472104516434, -7.951353249273225], [110.45856802264535, -7.960165632002253], [110.43595227237859, -7.996100539540755]]], "type": "Polygon"}, "id": "121", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.44440557137034, -8.018522399671339], [110.48470196015231, -8.014031893003557], [110.48840854100538, -7.95719636679338], [110.46809130147984, -7.955555270085402], [110.45856802264535, -7.960165632002253], [110.43595227237859, -7.996100539540755]]], "type": "Polygon"}, "id": "122", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.40357488926797, -8.045447776741923], [110.16240472313888, -8.398048155911845], [110.31439621295664, -8.076067560594417], [110.3802573554643, -7.988175121741584], [110.38731903423302, -7.989542477177513], [110.39074344495145, -7.992522862550108]]], "type": "Polygon"}, "id": "123", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.4378526127034, -8.036033978481873], [110.46185745782972, -8.063399501925884], [109.94655001946765, -9.573111024046028]]], "type": "Polygon"}, "id": "124", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.44440557137034, -8.018522399671339], [110.48470196015231, -8.014031893003557], [110.49351657901815, -8.026340432498984], [110.48580713970372, -8.053523344452074], [110.46185745782972, -8.063399501925884], [110.4378526127034, -8.036033978481873]]], "type": "Polygon"}, "id": "125", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.28458432196771, -7.831097553681192], [110.26252848597078, -7.830613696218737], [110.25630626527793, -7.847700871506009], [110.26169062881563, -7.870627838827829], [110.29453228488792, -7.852714208242958]]], "type": "Polygon"}, "id": "126", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.2869541326374, -7.828544442738712], [110.28458432196771, -7.831097553681192], [110.29453228488792, -7.852714208242958], [110.30147658227847, -7.861223417721513], [110.3249645390071, -7.837735460992908], [110.31385824439565, -7.826470505029873], [110.2899033714434, -7.827654586202417]]], "type": "Polygon"}, "id": "127", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.24122927927928, -7.745081788931791], [110.2203811056418, -7.723433472169635], [110.19462360224938, -7.759749952108021], [110.20151880903055, -7.776429785654859], [110.23282371724463, -7.765945594696379]]], "type": "Polygon"}, "id": "128", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.23738826772453, -7.8018395598337165], [110.213, -7.80705777027027], [110.19401176982078, -7.799231540263973], [110.20151880903055, -7.776429785654859], [110.23282371724463, -7.765945594696379]]], "type": "Polygon"}, "id": "129", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.26184984901862, -7.74734778560644], [110.28132866624841, -7.7342662220352745], [110.28217424914841, -7.728957245853018], [110.26749391320115, -7.700941317661205], [110.2196449074782, -7.704974567185748], [110.21623153742973, -7.713814018587119], [110.2203811056418, -7.723433472169635], [110.24122927927928, -7.745081788931791]]], "type": "Polygon"}, "id": "130", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.35880668781746, -7.90383698355935], [110.3658394943125, -7.907039071432785], [110.37430744899358, -7.930961043406819], [110.35657686183615, -7.944345898417821], [110.35375462211326, -7.907253604917]]], "type": "Polygon"}, "id": "131", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.2937422721817, -7.881702174314462], [110.26131972477064, -7.873815608727999], [110.2552735205238, -7.881250805842349], [110.2836277460067, -7.898849980280033]]], "type": "Polygon"}, "id": "132", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.26131972477064, -7.873815608727999], [110.26169062881563, -7.870627838827829], [110.25630626527793, -7.847700871506009], [110.22080409377187, -7.864897235829249], [110.2249776498726, -7.893938230363448], [110.23119996711475, -7.898312644666236], [110.2552735205238, -7.881250805842349]]], "type": "Polygon"}, "id": "133", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.2836277460067, -7.898849980280033], [110.2801510853724, -7.9156900552274285], [110.2646889037433, -7.918178222386134], [110.2338490461643, -7.9042015381631305], [110.23119996711475, -7.898312644666236], [110.2552735205238, -7.881250805842349]]], "type": "Polygon"}, "id": "134", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.2937422721817, -7.881702174314462], [110.30654607815195, -7.873661689017664], [110.30147658227847, -7.861223417721513], [110.29453228488792, -7.852714208242958], [110.26169062881563, -7.870627838827829], [110.26131972477064, -7.873815608727999]]], "type": "Polygon"}, "id": "135", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.2937422721817, -7.881702174314462], [110.30654607815195, -7.873661689017664], [110.30748964779318, -7.874094385693214], [110.31348129488708, -7.882463018771812], [110.29944098805167, -7.928168698470084], [110.2801510853724, -7.9156900552274285], [110.2836277460067, -7.898849980280033]]], "type": "Polygon"}, "id": "136", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.17906336779912, -7.82675509601182], [110.19227060402005, -7.799680261758897], [110.18301494112806, -7.795277312147876], [110.13803542555762, -7.806623496255741], [110.13660140345047, -7.828096090439126], [110.14073275540028, -7.829009837917625]]], "type": "Polygon"}, "id": "137", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.213, -7.826244999999999], [110.20068236476398, -7.849648506948432], [110.2197599244167, -7.863283519553075], [110.23037065555603, -7.837141138485148]]], "type": "Polygon"}, "id": "138", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.23037065555603, -7.837141138485148], [110.25451166518748, -7.823519674950072], [110.26252848597078, -7.830613696218737], [110.25630626527793, -7.847700871506009], [110.22080409377187, -7.864897235829249], [110.2197599244167, -7.863283519553075]]], "type": "Polygon"}, "id": "139", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.213, -7.826244999999999], [110.213, -7.80705777027027], [110.19401176982078, -7.799231540263973], [110.19227060402005, -7.799680261758897], [110.17906336779912, -7.82675509601182], [110.19079851694916, -7.849001483050848], [110.20068236476398, -7.849648506948432]]], "type": "Polygon"}, "id": "140", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.213, -7.826244999999999], [110.213, -7.80705777027027], [110.23738826772453, -7.8018395598337165], [110.24569737357182, -7.806113300751079], [110.25451166518748, -7.823519674950072], [110.23037065555603, -7.837141138485148]]], "type": "Polygon"}, "id": "141", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.65188095771701, -7.832313962348725], [110.64560494555856, -7.8895222270239485], [110.65043359624396, -7.9033643476738416], [110.6879658215465, -7.881568904468811], [110.65251906929295, -7.832034340422194]]], "type": "Polygon"}, "id": "142", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.65188095771701, -7.832313962348725], [110.62231192504454, -7.834097019595302], [110.61267498264873, -7.856096504256446], [110.64560494555856, -7.8895222270239485]]], "type": "Polygon"}, "id": "143", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.65043359624396, -7.9033643476738416], [110.6495743095893, -7.905122151686519], [110.62046733272165, -7.914702163282808], [110.61802559979047, -7.913797687585772], [110.60369587666747, -7.86299091312123], [110.61267498264873, -7.856096504256446], [110.64560494555856, -7.8895222270239485]]], "type": "Polygon"}, "id": "144", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.6879658215465, -7.881568904468811], [110.69457356402387, -7.880953016939324], [110.7132026558511, -7.893629617886849], [110.71480389908257, -7.896669266055047], [110.69242191824114, -7.936325930096226], [110.6633777389081, -7.927265031942042], [110.6495743095893, -7.905122151686519], [110.65043359624396, -7.9033643476738416]]], "type": "Polygon"}, "id": "145", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.65251906929295, -7.832034340422194], [110.65373491384845, -7.830756011349922], [110.66470228179571, -7.8290379472723455], [110.69024786228194, -7.836385505539284], [110.70027385620915, -7.8626758896150974], [110.69457356402387, -7.880953016939324], [110.6879658215465, -7.881568904468811]]], "type": "Polygon"}, "id": "146", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.65188095771701, -7.832313962348725], [110.62231192504454, -7.834097019595302], [110.58183549508867, -7.7918960299671305], [110.58498950681656, -7.699258199788368], [110.58751966044095, -7.689518841316383], [110.59049800935796, -7.683381409287651], [110.6120700507931, -7.6457818573585605], [110.65427905501802, -7.603305002471506], [110.65373491384845, -7.830756011349922], [110.65251906929295, -7.832034340422194]]], "type": "Polygon"}, "id": "147", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.32691361188469, -7.810018619169696], [110.31385824439565, -7.826470505029873], [110.2899033714434, -7.827654586202417], [110.31729474097332, -7.798007456828887], [110.32161449086162, -7.7987274151436035]]], "type": "Polygon"}, "id": "148", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.2547109606161, -7.798217398500303], [110.28877081280287, -7.791562025084497], [110.29286023504909, -7.784623058613509], [110.26877621359223, -7.7639796116504955]]], "type": "Polygon"}, "id": "149", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.28877081280287, -7.791562025084497], [110.2869541326374, -7.828544442738712], [110.2899033714434, -7.827654586202417], [110.31729474097332, -7.798007456828887], [110.29490179585615, -7.784071933043527], [110.29286023504909, -7.784623058613509]]], "type": "Polygon"}, "id": "150", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.26877621359223, -7.7639796116504955], [110.26184984901862, -7.74734778560644], [110.28132866624841, -7.7342662220352745], [110.30110684048874, -7.743106466582094], [110.30408414020805, -7.74771694527363], [110.30222312822211, -7.774208998250014], [110.29490179585615, -7.784071933043527], [110.29286023504909, -7.784623058613509]]], "type": "Polygon"}, "id": "151", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.2547109606161, -7.798217398500303], [110.24569737357182, -7.806113300751079], [110.25451166518748, -7.823519674950072], [110.26252848597078, -7.830613696218737], [110.28458432196771, -7.831097553681192], [110.2869541326374, -7.828544442738712], [110.28877081280287, -7.791562025084497]]], "type": "Polygon"}, "id": "152", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.2547109606161, -7.798217398500303], [110.24569737357182, -7.806113300751079], [110.23738826772453, -7.8018395598337165], [110.23282371724463, -7.765945594696379], [110.24122927927928, -7.745081788931791], [110.26184984901862, -7.74734778560644], [110.26877621359223, -7.7639796116504955]]], "type": "Polygon"}, "id": "153", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.33030281360722, -7.925412112373021], [110.348081572133, -7.909369883749763], [110.32164785884218, -7.890307109741951], [110.32428668153958, -7.924205832085346]]], "type": "Polygon"}, "id": "154", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.348081572133, -7.909369883749763], [110.35375462211326, -7.907253604917], [110.35880668781746, -7.90383698355935], [110.35619717727121, -7.882620528248559], [110.32007973938975, -7.88706364899419], [110.32164785884218, -7.890307109741951]]], "type": "Polygon"}, "id": "155", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.32428668153958, -7.924205832085346], [110.30067080282757, -7.929660418244555], [110.29944098805167, -7.928168698470084], [110.31348129488708, -7.882463018771812], [110.32007973938975, -7.88706364899419], [110.32164785884218, -7.890307109741951]]], "type": "Polygon"}, "id": "156", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.33030281360722, -7.925412112373021], [110.34169929582798, -7.942793339447131], [110.35270272636808, -7.949183651337331], [110.35657686183615, -7.944345898417821], [110.35375462211326, -7.907253604917], [110.348081572133, -7.909369883749763]]], "type": "Polygon"}, "id": "157", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.33030281360722, -7.925412112373021], [110.34169929582798, -7.942793339447131], [110.31844175268664, -7.957270618725235], [110.30064942869699, -7.929840785907855], [110.30067080282757, -7.929660418244555], [110.32428668153958, -7.924205832085346]]], "type": "Polygon"}, "id": "158", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.3710143667192, -7.870877178810005], [110.39527938608923, -7.88770245167508], [110.39745742694953, -7.899873856482655], [110.3658394943125, -7.907039071432785], [110.35880668781746, -7.90383698355935], [110.35619717727121, -7.882620528248559], [110.35635513604782, -7.8822001707768505]]], "type": "Polygon"}, "id": "159", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.15305405599698, -7.867832434435265], [110.16010576924478, -7.847597335355893], [110.17780816593095, -7.861991834069046], [110.17255349672622, -7.875196827110218], [110.16122687111869, -7.877403721623861]]], "type": "Polygon"}, "id": "160", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.17780816593095, -7.861991834069046], [110.19079851694916, -7.849001483050848], [110.17906336779912, -7.82675509601182], [110.14073275540028, -7.829009837917625], [110.16010576924478, -7.847597335355893]]], "type": "Polygon"}, "id": "161", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.15305405599698, -7.867832434435265], [110.12915023577854, -7.842990844892911], [110.1316037662451, -7.832959013671992], [110.13660140345047, -7.828096090439126], [110.14073275540028, -7.829009837917625], [110.16010576924478, -7.847597335355893]]], "type": "Polygon"}, "id": "162", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.17255349672622, -7.875196827110218], [110.1934116961013, -7.898877940686439], [110.2249776498726, -7.893938230363448], [110.22080409377187, -7.864897235829249], [110.2197599244167, -7.863283519553075], [110.20068236476398, -7.849648506948432], [110.19079851694916, -7.849001483050848], [110.17780816593095, -7.861991834069046]]], "type": "Polygon"}, "id": "163", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.16122687111869, -7.877403721623861], [110.15921353459163, -7.879241812176223], [110.15378595313733, -7.911562478930173], [110.17528970492279, -7.9258502066265555], [110.1934116961013, -7.898877940686439], [110.17255349672622, -7.875196827110218]]], "type": "Polygon"}, "id": "164", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.15305405599698, -7.867832434435265], [110.12915023577854, -7.842990844892911], [110.11480601506184, -7.863767942199554], [110.13045611340114, -7.885968914785161], [110.15921353459163, -7.879241812176223], [110.16122687111869, -7.877403721623861]]], "type": "Polygon"}, "id": "165", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.39891249570063, -7.854171833940976], [110.40138849023754, -7.877817581768445], [110.42593170858179, -7.871532123411973], [110.40026352191482, -7.852417516319547]]], "type": "Polygon"}, "id": "166", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.40138849023754, -7.877817581768445], [110.39527938608923, -7.88770245167508], [110.39745742694953, -7.899873856482655], [110.41058664779524, -7.911902651303725], [110.438749715804, -7.902928848070472], [110.45178543424488, -7.877414096673725], [110.45060708403653, -7.875122737395989], [110.44692483779737, -7.873810447512884], [110.42593170858179, -7.871532123411973]]], "type": "Polygon"}, "id": "167", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.39891249570063, -7.854171833940976], [110.37278675896042, -7.862446954175434], [110.3710143667192, -7.870877178810005], [110.39527938608923, -7.88770245167508], [110.40138849023754, -7.877817581768445]]], "type": "Polygon"}, "id": "168", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.40245679606092, -7.8456327149891205], [110.40026352191482, -7.852417516319547], [110.42593170858179, -7.871532123411973], [110.44692483779737, -7.873810447512884], [110.41338482293423, -7.843681281618888]]], "type": "Polygon"}, "id": "169", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.4324338863892, -7.825337739032626], [110.45119534975376, -7.86843337765223], [110.45060708403653, -7.875122737395989], [110.44692483779737, -7.873810447512884], [110.41338482293423, -7.843681281618888]]], "type": "Polygon"}, "id": "170", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.43277857155195, -7.823145315374451], [110.45621172886702, -7.8185043329191934], [110.46226968497625, -7.824926888238714], [110.46016105258357, -7.851346811747089], [110.45119534975376, -7.86843337765223], [110.4324338863892, -7.825337739032626]]], "type": "Polygon"}, "id": "171", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.40543851641085, -7.735752588867069], [110.39689939495025, -7.732991996175694], [110.39740214496368, -7.708482933021196], [110.42583400694595, -7.705791159105697], [110.43595228079708, -7.72946069257888], [110.43483301911495, -7.730564152919619], [110.42479868801308, -7.735258706938453]]], "type": "Polygon"}, "id": "172", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.34050569642876, -7.862553728246612], [110.35635513604782, -7.8822001707768505], [110.35619717727121, -7.882620528248559], [110.32007973938975, -7.88706364899419], [110.31348129488708, -7.882463018771812], [110.30748964779318, -7.874094385693214], [110.33391039147949, -7.860234494344235]]], "type": "Polygon"}, "id": "173", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.3341944927319, -7.839305702083024], [110.3249645390071, -7.837735460992908], [110.30147658227847, -7.861223417721513], [110.30654607815195, -7.873661689017664], [110.30748964779318, -7.874094385693214], [110.33391039147949, -7.860234494344235]]], "type": "Polygon"}, "id": "174", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.33259120847096, -7.758291159898971], [110.34713394702472, -7.776968598629793], [110.33745941210164, -7.78599148094147], [110.33109044117647, -7.787436921151437], [110.3221233284202, -7.772173750502478], [110.32880306572734, -7.757673832933343]]], "type": "Polygon"}, "id": "175", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.32880306572734, -7.757673832933343], [110.3271016271767, -7.75566468741079], [110.30408414020805, -7.74771694527363], [110.30222312822211, -7.774208998250014], [110.3221233284202, -7.772173750502478]]], "type": "Polygon"}, "id": "176", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.33109044117647, -7.787436921151437], [110.32161449086162, -7.7987274151436035], [110.31729474097332, -7.798007456828887], [110.29490179585615, -7.784071933043527], [110.30222312822211, -7.774208998250014], [110.3221233284202, -7.772173750502478]]], "type": "Polygon"}, "id": "177", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.3428134817125, -7.817794598809174], [110.3452298013245, -7.8311649006622535], [110.3341944927319, -7.839305702083024], [110.3249645390071, -7.837735460992908], [110.31385824439565, -7.826470505029873], [110.32691361188469, -7.810018619169696], [110.34275172503018, -7.817655970172658]]], "type": "Polygon"}, "id": "178", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.35092855723674, -7.748795032859541], [110.33259120847096, -7.758291159898971], [110.32880306572734, -7.757673832933343], [110.3271016271767, -7.75566468741079], [110.33539794103234, -7.721294244294581], [110.35457129202847, -7.735405521192651]]], "type": "Polygon"}, "id": "179", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.37331979968125, -7.732479414435464], [110.37309709175318, -7.711396911243172], [110.35653727566213, -7.699518896625509], [110.33300327859591, -7.714173926451192], [110.3336213618011, -7.718806140127597], [110.33539794103234, -7.721294244294581], [110.35457129202847, -7.735405521192651]]], "type": "Polygon"}, "id": "180", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.37985, -7.736549728997289], [110.39689939495025, -7.732991996175694], [110.39740214496368, -7.708482933021196], [110.39113795679062, -7.701687237972853], [110.38600367666373, -7.701632423594275], [110.37309709175318, -7.711396911243172], [110.37331979968125, -7.732479414435464]]], "type": "Polygon"}, "id": "181", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.35035970388869, -7.80389244478319], [110.34275172503018, -7.817655970172658], [110.3428134817125, -7.817794598809174], [110.37077248157247, -7.814089189189198], [110.37098431754875, -7.813830278551532], [110.35909184788864, -7.802584138764244], [110.35695144240783, -7.801847948344095]]], "type": "Polygon"}, "id": "182", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.35035970388869, -7.80389244478319], [110.34275172503018, -7.817655970172658], [110.32691361188469, -7.810018619169696], [110.32161449086162, -7.7987274151436035], [110.33109044117647, -7.787436921151437], [110.33745941210164, -7.78599148094147], [110.3483000138236, -7.800120804534142]]], "type": "Polygon"}, "id": "183", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.35387669902913, -7.773749029126217], [110.35976424692288, -7.76618442213545], [110.35092855723674, -7.748795032859541], [110.33259120847096, -7.758291159898971], [110.34713394702472, -7.776968598629793], [110.3486967144564, -7.7767090203106335]]], "type": "Polygon"}, "id": "184", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.36988191657744, -7.765129684372238], [110.35976424692288, -7.76618442213545], [110.35092855723674, -7.748795032859541], [110.35457129202847, -7.735405521192651], [110.37331979968125, -7.732479414435464], [110.37985, -7.736549728997289], [110.37985, -7.743515384615382], [110.37223993400832, -7.764101588772376]]], "type": "Polygon"}, "id": "185", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.40870529864311, -7.818932964872976], [110.425653148662, -7.813712063208389], [110.43277857155195, -7.823145315374451], [110.4324338863892, -7.825337739032626], [110.41338482293423, -7.843681281618888], [110.40245679606092, -7.8456327149891205], [110.39677306890763, -7.8364007651043]]], "type": "Polygon"}, "id": "186", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.35270588508956, -7.853015398929985], [110.34887723577236, -7.832988617886181], [110.36409511502153, -7.8338644670515984], [110.37102485955056, -7.8390771067415725], [110.37160737583613, -7.859964476410341]]], "type": "Polygon"}, "id": "187", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.37102485955056, -7.8390771067415725], [110.38903356368641, -7.832416353157079], [110.38371120590526, -7.809457162728594], [110.37098431754875, -7.813830278551532], [110.37077248157247, -7.814089189189198], [110.36409511502153, -7.8338644670515984]]], "type": "Polygon"}, "id": "188", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.34887723577236, -7.832988617886181], [110.3452298013245, -7.8311649006622535], [110.3428134817125, -7.817794598809174], [110.37077248157247, -7.814089189189198], [110.36409511502153, -7.8338644670515984]]], "type": "Polygon"}, "id": "189", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.35270588508956, -7.853015398929985], [110.34050569642876, -7.862553728246612], [110.33391039147949, -7.860234494344235], [110.3341944927319, -7.839305702083024], [110.3452298013245, -7.8311649006622535], [110.34887723577236, -7.832988617886181]]], "type": "Polygon"}, "id": "190", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.37160737583613, -7.859964476410341], [110.37278675896042, -7.862446954175434], [110.39891249570063, -7.854171833940976], [110.40026352191482, -7.852417516319547], [110.40245679606092, -7.8456327149891205], [110.39677306890763, -7.8364007651043], [110.38903356368641, -7.832416353157079], [110.37102485955056, -7.8390771067415725]]], "type": "Polygon"}, "id": "191", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.35270588508956, -7.853015398929985], [110.34050569642876, -7.862553728246612], [110.35635513604782, -7.8822001707768505], [110.3710143667192, -7.870877178810005], [110.37278675896042, -7.862446954175434], [110.37160737583613, -7.859964476410341]]], "type": "Polygon"}, "id": "192", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.36435000000004, -7.79007499999998], [110.35021635514028, -7.779474766355311], [110.3543835448776, -7.787446781504983], [110.35936077987121, -7.792853088480802]]], "type": "Polygon"}, "id": "193", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.35936077987121, -7.792853088480802], [110.35695144240783, -7.801847948344095], [110.35035970388869, -7.80389244478319], [110.3483000138236, -7.800120804534142], [110.3543835448776, -7.787446781504983]]], "type": "Polygon"}, "id": "194", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.35021635514028, -7.779474766355311], [110.3486967144564, -7.7767090203106335], [110.34713394702472, -7.776968598629793], [110.33745941210164, -7.78599148094147], [110.3483000138236, -7.800120804534142], [110.3543835448776, -7.787446781504983]]], "type": "Polygon"}, "id": "195", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.39881920990778, -7.766862104501903], [110.37985, -7.743515384615382], [110.37223993400832, -7.764101588772376], [110.39379044293015, -7.776881541737649]]], "type": "Polygon"}, "id": "196", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.39888787045727, -7.76680750301731], [110.40543851641085, -7.735752588867069], [110.39689939495025, -7.732991996175694], [110.37985, -7.736549728997289], [110.37985, -7.743515384615382], [110.39881920990778, -7.766862104501903]]], "type": "Polygon"}, "id": "197", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.41664917348182, -7.763022307290754], [110.42479868801308, -7.735258706938453], [110.40543851641085, -7.735752588867069], [110.39888787045727, -7.76680750301731]]], "type": "Polygon"}, "id": "198", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.43293109603478, -7.78429385127124], [110.4371874256429, -7.782683084332388], [110.44085906686816, -7.778772534945221], [110.43483301911495, -7.730564152919619], [110.42479868801308, -7.735258706938453], [110.41664917348182, -7.763022307290754]]], "type": "Polygon"}, "id": "199", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.42382769623198, -7.79383491452609], [110.425653148662, -7.813712063208389], [110.43277857155195, -7.823145315374451], [110.45621172886702, -7.8185043329191934], [110.46018015654442, -7.805995158718659], [110.4371874256429, -7.782683084332388], [110.43293109603478, -7.78429385127124]]], "type": "Polygon"}, "id": "200", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.38509486535632, -7.8071143757035175], [110.38371120590526, -7.809457162728594], [110.38903356368641, -7.832416353157079], [110.39677306890763, -7.8364007651043], [110.40870529864311, -7.818932964872976], [110.38796638110072, -7.804925099515403]]], "type": "Polygon"}, "id": "201", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.39720770953295, -7.788862790573682], [110.42382769623198, -7.79383491452609], [110.425653148662, -7.813712063208389], [110.40870529864311, -7.818932964872976], [110.38796638110072, -7.804925099515403]]], "type": "Polygon"}, "id": "202", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.39631081791956, -7.787083955540462], [110.39720770953295, -7.788862790573682], [110.42382769623198, -7.79383491452609], [110.43293109603478, -7.78429385127124], [110.41664917348182, -7.763022307290754], [110.39888787045727, -7.76680750301731], [110.39881920990778, -7.766862104501903], [110.39379044293015, -7.776881541737649], [110.39431243945398, -7.781644760017622]]], "type": "Polygon"}, "id": "203", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.37370853899309, -7.798198667324773], [110.38509486535632, -7.8071143757035175], [110.38371120590526, -7.809457162728594], [110.37098431754875, -7.813830278551532], [110.35909184788864, -7.802584138764244], [110.3701128002044, -7.796988886050074]]], "type": "Polygon"}, "id": "204", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.36554166666666, -7.789479166666668], [110.36435000000004, -7.79007499999998], [110.35936077987121, -7.792853088480802], [110.35695144240783, -7.801847948344095], [110.35909184788864, -7.802584138764244], [110.3701128002044, -7.796988886050074]]], "type": "Polygon"}, "id": "205", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.3738942831216, -7.789468693284937], [110.39631081791956, -7.787083955540462], [110.39720770953295, -7.788862790573682], [110.38796638110072, -7.804925099515403], [110.38509486535632, -7.8071143757035175], [110.37370853899309, -7.798198667324773]]], "type": "Polygon"}, "id": "206", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.36717656249999, -7.78571890625], [110.35387669902913, -7.773749029126217], [110.3486967144564, -7.7767090203106335], [110.35021635514028, -7.779474766355311], [110.36435000000004, -7.79007499999998], [110.36554166666666, -7.789479166666668]]], "type": "Polygon"}, "id": "207", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.37026320229725, -7.786153358619233], [110.3807215760002, -7.782083174967738], [110.37135427034579, -7.778544463150494], [110.36769812333048, -7.785546389975301]]], "type": "Polygon"}, "id": "208", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.3807215760002, -7.782083174967738], [110.39431243945398, -7.781644760017622], [110.39379044293015, -7.776881541737649], [110.37223993400832, -7.764101588772376], [110.36988191657744, -7.765129684372238], [110.37135427034579, -7.778544463150494]]], "type": "Polygon"}, "id": "209", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.36769812333048, -7.785546389975301], [110.36717656249999, -7.78571890625], [110.35387669902913, -7.773749029126217], [110.35976424692288, -7.76618442213545], [110.36988191657744, -7.765129684372238], [110.37135427034579, -7.778544463150494]]], "type": "Polygon"}, "id": "210", "properties": {}, "type": "Feature"}, {"geometry": {"coordinates": [[[110.37026320229725, -7.786153358619233], [110.3738942831216, -7.789468693284937], [110.39631081791956, -7.787083955540462], [110.39431243945398, -7.781644760017622], [110.3807215760002, -7.782083174967738]]], "type": "Polygon"}, "id": "211", "properties": {}, "type": "Feature"}], "type": "FeatureCollection"});
        
</script>
