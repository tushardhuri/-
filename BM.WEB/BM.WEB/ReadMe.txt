Get started with ASP.NET Core MVC
https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-mvc-app/start-mvc?view=aspnetcore-2.2&tabs=visual-studio

.Net Documentation
https://docs.microsoft.com/en-gb/dotnet/

Introduction to Identity on ASP.NET Core
https://docs.microsoft.com/en-gb/aspnet/core/security/authentication/identity?view=aspnetcore-2.2&tabs=visual-studio

crossorigin attribute in script tag
By default (that is, when the attribute is not specified), CORS is not used at all. 
The "anonymous" keyword means that there will be no exchange of user credentials via cookies, client-side SSL certificates or HTTP authentication as described in the Terminology section of the CORS specification, unless it is in the same origin.


Difference Between Obstrusive and Unobtrusive javascript ?
Unobstrusive:- (Good)
Separate HTML, CSS and JavaScript
Obstrusive:- (Avoid)
The javascript tied with html markup.

Examples:-
eg.Unobstrusive:-

<div id="main">Unobtrusive JS Example</div>

<script type="text/javascript">
$(function() {
$("#main").click(function() { alert("unobtrusive!"); }
});
</script>

eg. Obstrusive:-

<div id="main" onclick="alert('obstrusive')">Obtrusive JS Example</div>


