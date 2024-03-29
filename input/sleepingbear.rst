************************************************
Sleeping Bear Dunes
************************************************

Overview TBD


* Owner: National Park Service
* Fees: None.
* Permit: NPS issues one annual permit for all sites at the `Philip Hart Visitor Center <https://www.google.com/maps/place/Philip+A.+Hart+Visitor+Center/@44.8116366,-86.058379,17z/data=!3m1!4b1!4m5!3m4!1s0x881e1af9c6058f8f:0xf4e22c9117e103ea!8m2!3d44.8116328!4d-86.0561903?hl=en&authuser=0>`_.
* Understand the weather and learn about :ref:`eval`.

.. tip:: Pilots must have the phone photo or physical permit in hand when using any National Lakeshore land. 

`Rules and maps in PDF <parksitesjune22.pdf>`_

.. image:: images/sleepingbear.png

Park rules
============================

Intro: tbd

`Link to park regulations <parksitesjune22.pdf>`_.

Details
======================

* Flying is limited to 5 gliders at a time.
* Avoid spectators. It may be too crowded to fly holidays.
* No kiting. 
* Check the LZ. The beach may be crowded or nonexistent due to high water. 
* Remove streamers and telltales. 


.. raw:: html

            <section id="motor-database">

                <p><a class="reference external"
                    href="https://docs.google.com/spreadsheets/d/1yiO-VzdGjWFEVoA9B0QAauQndoyHSNJork9m4a6oHI8/edit?usp=sharing">Edit
                    or copy this data</a> </p>

                <!-- Table sorter -->
                <table class="blueTable">
                  <thead id="table-head"></thead>
                  <tbody id="table-body"></tbody>
                </table>
                <!-- Table -->

                <!-- MDB ESSENTIAL -->
                <script type="text/javascript" src="js/mdb.min.js"></script>
                <!-- Google API -->
                <script src="https://apis.google.com/js/api.js"></script>
                <!-- easyData -->
                <script type="text/javascript" src="js/easyData-google-sheets.js"></script>

                <!-- easyData - Creating table -->
                <script>
                  {
                    {
                      const API_KEY = "AIzaSyDhOS3VJZ66Utl0lnHbSK8gH0BXz-wxRoU";


                      function displayResult2(response) {
                        let tableHead = "";
                        let tableBody = "";

                        response.result.values.forEach((row, index) => {
                          if (index === 0) {
                            tableHead += "<tr>";
                            row.forEach((val) => (tableHead += "<th>" + val + "</th>"));
                            tableHead += "</tr>";
                          } else {
                            tableBody += "<tr>";
                            row.forEach((val) => (tableBody += "<td>" + val + "</td>"));
                            tableBody += "</tr>";
                          }
                        });

                        document.getElementById("table-head").innerHTML = tableHead;
                        document.getElementById("table-body").innerHTML = tableBody;

                      }

                      function loadData() {
                        const spreadsheetId = "1yiO-VzdGjWFEVoA9B0QAauQndoyHSNJork9m4a6oHI8";
                        const range = "!A:C";
                        getPublicValues({ spreadsheetId, range }, displayResult2);
                      }

                      window.addEventListener("load", (e) => {
                        initOAuthClient({ apiKey: API_KEY });
                      });

                      document.addEventListener("gapi-loaded", (e) => {
                        loadData();
                      });
                    }
                  }
                </script>

              </section>

Video
==================


Hang gliding 
-----------------


.. raw:: html

  <iframe width="560" height="315" src="https://www.youtube.com/embed/RUQiH4GCDhs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
  
Paragliding
------------------------

.. raw:: html

 <iframe width="560" height="315" src="https://www.youtube.com/embed/UNNqsLnez6g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Photos
---------------------------

tbd

