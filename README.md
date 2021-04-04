# Summary

<p>
This project uses the <a href="https://pypi.org/project/nba-api/">"nba-api 1.1.9"</a> as a use case for understanding the topic of <b>REST API clients</b>. The nba-api is a an API Client package to access the APIs for NBA.com. The project is inspired by the Coursera IBM course: "Python for Data Science, AI & Development".
</p>

<p>
<b>What is an API?</b><br>
"An <b>API</b> is a set of definitions and protocols for building and integrating application software. It’s sometimes referred to as a contract between an information provider and an information user—establishing the content required from the consumer (the call) and the content required by the producer (the response). For example, the API design for a weather service could specify that the user supply a zip code and that the producer reply with a 2-part answer, the first being the high temperature, and the second being the low."<br>
<a href="https://www.redhat.com/en/topics/api/what-is-a-rest-api">Redhat</a> 
</p> 


<p>
<b>What is a RESTful API?</b><br>
Software systems can share data. "The Restful API (Representational State Transfer) works to give the client a series of results once they link to the URL. For Restful API to work, one has to use the correct HTTP procedures. These procedures specify the operation that needs to be carried out with the API.The client sends a call to the server for a given resource. Usually, it is an HTTP request. The server receives the request and starts processing the response by checking the available cache resources that include the requested tag header." The server then sends a response back.<br>
<a href="https://rapidapi.com/blog/api-glossary/what-is-a-restful-api-understanding-the-restful-api-definition/">Visit api-glossary</a> 
</p>

### Practical approaches:
<p>
It is helpful to study the rules, proctocols and conceptualization of the API. It is often less strenuous than do trial and error. Also the API's maintained by communities but also by enterprises are prone to disfunction and must be validated regularly. As the data architecture of the data provider NBA changes the 
API's should be adapted. This is not always the case as the adaption relies on the community. The server site can then create issues, which are not solved by the client-API-site. The file 
<a href="https://github.com/swar/nba_api/blob/master/analysis_archive/stats/analysis.json" target="_blank">analysis.json</a> offers an overview about the validation state for the NBA API.<br>
Below an example of a dysfunctional API at this point is given with:<br>
<b>An example for a dysfunctional endpoint: LeagueGameFinder</b>
</p>