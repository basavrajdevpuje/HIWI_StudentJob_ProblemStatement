# HIWI_StudentJob_ProblemStatement

This animation shows how routing and address resolution interact during data transmission.

**Extra link in the index.html

👇👇👇👇👇👇👇👇👇👇👇👇👇

<a href="" onclick="window.location.href = window.location.href" class="refresh">Click here to refresh the page</a>

The above link is to refresh the page and to clear the cache stored. The *"page reload button" on Chrome browser works fine, but if we load the same webpage on the *firefox to force refresh the page then every time we have to press ctrl + f5. So the link above will do the work same as ctrl +f5.

**Function in javaScript

var next_last_transmission = function() {
}

The above function will check the number of times "Next" button is clicked. In the case of this problem statement, when first time the "Next" button is clicked then
next() will be called. When we again click the "Next" button for last transmission then the next() is again gets called. To avoid this next_last_transmission()
have a counter "timesClicked" which will get incremented for every click.
Function call for EVEN number of click and ODD number of click is different.
