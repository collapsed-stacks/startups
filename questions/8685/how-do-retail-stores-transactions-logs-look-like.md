## How do retail stores' transactions logs look like?

- posted by: [Jack Twain](https://stackexchange.com/users/2871380/jack-twain) on 2016-03-08
- tagged: `data`
- score: 2

<p>I would like to build a service that does some predictive analysis for retail stores. However I have completely no idea how retail houses stores their data and what software they use. I have also no friends whatsoever in that business to ask them. Thus I'm asking here if you know how such logs look like. Do you know some of the most famous and used software? Is there some kind of a standard formatting for that data of how it looks like?</p>

<p>Edit: in order for my service to work, it needs to have data inserted to it. Not knowing the format for retail stores data would mean the customers have to adapt their data to my service, which no customer would be willing to do.</p>



## Answer 8701

- posted by: [zazaalaza](https://stackexchange.com/users/4672194/zazaalaza) on 2016-03-10
- score: 1

<p>I'm guessing you're referring to financial transactions.</p>

<p>There is no universal program but most of the big companies use one of the following systems: Infor, Oarcle, SAP, NetSuite. <a href="https://en.wikipedia.org/wiki/List_of_ERP_software_packages#Proprietary_ERP_vendors_and_software" rel="nofollow">Here is a bigger list</a> . </p>

<p>These are called ERP Systems. (Enterprise resource planning)</p>

<p>Most of them store their data in an ODBC compatible database, the most prominent beeing: SQL, Access, CSV/TXT, AS400 DB2, Excel, etc.</p>

<p>Edit: Making your system read directly from the database would be your best bet.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
