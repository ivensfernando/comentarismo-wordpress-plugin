# Comentarismo WordPress Plugin

## Welcome to Comentarismo WordPress Plugin




# License: [license.md]()
```
Author: CreativeMindsSolutions
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
```


```
.hidden {
	display:none !important;
}
```


```
<script src="http://api.comentarismo.com/static/js/build/comentarismo-client.js"></script>
<script type="text/javascript">
    $(function () {
        var comentarismo = new Comentarismo({
            icons:{
                commenticon: "http://api.comentarismo.com/static/img/comentarismo_add_comment.jpg",
                thumbsup: "http://api.comentarismo.com/static/img/thumbs-up.jpg",
                thumbsdown: "http://api.comentarismo.com/static/img/thumbs-down.jpg",
                replybtn: "<img src='http://api.comentarismo.com/static/img/comentarismo_reply.jpg' style='width: 10px;height: 10px;'/>"
            },
            selector:"#comments",
            cached:"api.comentarismo.com/elk",
            host: "localhost:3000",
            css: "http://api.comentarismo.com/static/css/custom.css",
            debug: "true",
            forum: "comentarismo",
            table: "commentaries",
            operator: "g1",
            page: "g1texas-comeca-2016-com-lei-que-permite-porte-aberto-de-armas",
            key: "HL3Q87OdXRXiun8LSyAy5vmCDJJCfyVrX97aIk_Ll2JcC0IG2yUpRoBOB7O6qRkDUAd6yQbD4gY="
        });
        comentarismo.connect();
    });
</script>
```