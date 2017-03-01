<!-- Project Logo -->
<h3 align="center">
<a href="/" style="text-decoration: none">
  <img src='Resources/Placeholder/LogoHolder.png' width=200px>
  <br/>
  Nifty<sup>&#153;</sup>
</a></h3>

<!-- Bullets -->
<p align="center">
  Clean &bull;
  Classic &bull;
  Robust
</p>

-----
# Nifty API
Nifty is a made up music API. Nifty has a large database of over 500k songs. It provides features like:
- Music and Artist data
- Similar song and artist matching
- Audio analysis
- JSON and Google Protobuf support

Nifty is one of the best Music APIs out there. Leveraging machine learning, Nifty only gets smarter as more music is put into the service. Providing developers with the best music matching and analysis service is what we do best.


# Official SDKs
Platform | Link
-------- | -----
iOS      | <a href="LINK TO EXTERNAL GITHUB"><img src="https://img.shields.io/badge/SwiftyNifty-v1.7-blue.svg"/></a>
Android  | <a href="LINK TO EXTERNAL GITHUB"><img src="https://img.shields.io/badge/AndroidNifty-v1.5.1-blue.svg"/></a>
Python   | <a href="LINK TO EXTERNAL GITHUB"><img src="https://img.shields.io/badge/NiftyPy-v1.3-blue.svg"/></a>


# Documentation
Documentation for the API can be found [on our site]().


# Example Use
`curl -H "Content-Type: application/json" http://nifty:3000/api/similartrack?song=She+Will+Be+Loved&count=2`
<details>
<summary><b>JSON Result</b></summary>
```
{
	"resultCount":1,
	"results": [
		{
			"title": "When I was Your Man",
			"songId":294017
		},
		{
			"title": "Harder to Breathe",
			"songId":74428
		}
	]
}
```
</details>
