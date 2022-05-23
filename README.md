# Fetch-API-in-Web-Page-
Fetch Data from API in Web Page
<!DOCTYPE HTML>
<html>
<head>
<title>Fetch</title>    
</head>
    <body>
    <h1>Fetch</h1>
        <script>
        fetch('https://swapi.dev/api/people/1/')
          .then(function(responce){
            return responce.json()
        })
            .then(function(res){
            console.log(res)
        })
        </script>
    </body>
</html>
