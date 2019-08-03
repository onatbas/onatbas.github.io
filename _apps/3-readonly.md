---
order: 3
message_1: Use read-only
link: tagger
message_2: for <div id="evernote"></div>, it's hosted on <div id="predix"></div>.
---

<html>

<head>
    <link href="https://fonts.googleapis.com/css?family=Lato" rel="stylesheet">

    <style>
        html {
            background: url('/resources/LY5TUv5.jpg') no-repeat center fixed;
            -webkit-background-size: cover;
            -moz-background-size: cover;
            -o-background-size: cover;
            background-size: cover;
        }
        
        body {
            font-family: 'Lato', Helvetica, Arial, sans-serif;
        }
        
        #container {
            width: 80%;
            min-height: 400px;
            text-align: center;
            margin: auto;
            margin-top: 25px;
        }
        
        #howitworks {
            padding: 50px;
            border: 1px solid #efefef;
            border-radius: 15px;
            background-color: #fefefe;
            min-height: 400px;
        }
        
        h1 {
            display: inline;
            color: #efefef;
            text-shadow: #000000 0 0 10px;
        }
        
        h2 {
            margin-top: 40px;
            color: #454545;
            font-size: 36px;
        }
        p{
            line-height: 1.5;
        }
    </style>
</head>

<body>


    <div id="container">

        <img src="/resources/Logomakr_2Xu2q4.png" width="200px" height="auto"><br>
        <h1>Evernote ReadOnlyMaker</h1>

        <div id="howitworks" style="margin-top:20px">

            <p>Are you deleting valuable information from your notes by mistake? Or simply your upload quote is filing up because opening and closing PDFs, images etc. are treated as uploads? Make your notes read-only with this. </p>
            <hr>

            <h2>How It Works?</h2>

            <p>That's easy! First, you log in.</p>

            <a href="https://ro-app.run.aws-usw02-pr.ice.predix.io/">Login with Evernote</a>

            <p>And then you tag your notes "readonly".</p>

<iframe src="https://giphy.com/embed/xUPGcovmwWWgL1Doje" width="480" height="266" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>
       
            <p>Sync your notes</p>

<iframe src="https://giphy.com/embed/xUPGcoU3PyJ6sGKecM" width="480" height="137.5796178343949" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>            
       
            <p>Give the app a minute or so to capture it. Then refresh your note see it in readonly mode, forever!</p>
            
<iframe src="https://giphy.com/embed/xUPGcG3GBaRjEg66Va" width="480" height="210" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

	

            <hr>
            <h2>What If I Need to Make Changes!??</h2>
	    <p>Yep, I got you covered on that, too. But unfortunately a readonly note itself can not be directly edited (readonly, duh). But there's a workaround.</p> 

	    <p>Basically, you add the tag "unlock" to any note you want to make modifications.</p>

		<p>This will create a duplicate of the same note in your default notebook, which you can edit (title and content only).</p>
		
		<p>After you're done with it, add "makemigration" tag to this duplicate, without changing prior tags, and sync.</p>

		<p>After a minute or so, this duplicate will be deleted and your original will be updated with the content you provided in the duplicate.</p>

		<p>Note: I realize this is not a straightforward way of doing it. But If you think about it, deleteing and creating new notes all the time will result in broken note links all over other notes, so original must be preserved. If you're fine with breaking links etc, you may as well just use the duplicate and delete original. It's up to you. But really, don't make changes on readonly notes.</p>
	

		<h2>Supported on all platforms</h2>
		<p>ReadOnlyTagger works with native evernote tags, so it's available on all platforms.</p>
	            
            <p>Got Feedback? <a href="http://onat.me">Reach out!</a></p>
        </div>


    </div>


</body>

</html>