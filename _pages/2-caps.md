---
order: 2
message_1: Make
link: caps.
message_2: 
---

<!DOCTYPE html>
<html>
<head>
    <title></title>

    <script type="text/javascript">

    function submit()
    {
        var text = document.getElementById("text_").value;
        var link = document.getElementById("link_").value;
        document.getElementById("ptext").innerHTML = text;
        document.getElementById("pic").src = link;
    }

    function hide()
    {
        document.getElementById("gui").style.display = "none";
    }
    </script>


    <style type="text/css">

    #gui{
        margin: 30px;
        padding: 10px;
        border: 1px solid #444;
        border-radius: 3px;
    }

    #page{
        width: 400px;
    }

    img{
        margin: 0px;
        margin-bottom: -4px;
        width: 100%;
        height: auto;
    }

    p{
        padding: 15px;
        padding-left: 10px; padding-right: 10px;
        text-transform: uppercase;
        font-family: Tahoma, 'Gill Sans';
        color: #ffffff;
        font-size: 22px;
        background-color: #ff0000;
        margin: 0px;
        text-align: center;
    }



    </style>
</head>
<body>

<div id="gui">
    
<textarea id="text_">lipsum</textarea>
<textarea id="link_">http://ilberortayli.com/images/haber/57.jpg</textarea>
<button onclick="submit()">Submit</button>
<button onclick="hide()">remove for printing</button>

</div>


<div id="page">
    <img id="pic" src="moon.jpg"/>
    <p id="ptext">Lorem ipsum dolor sit amet</p>

</div>

</body>
</html>