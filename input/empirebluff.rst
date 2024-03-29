************************************************
Empire Bluff
************************************************

Overview TBD

* Owner: National Park Service
* Fees: None.
* Permit: NPS issues one annual permit for all sites at the `Philip Hart Visitor Center <https://www.google.com/maps/place/Philip+A.+Hart+Visitor+Center/@44.8116366,-86.058379,17z/data=!3m1!4b1!4m5!3m4!1s0x881e1af9c6058f8f:0xf4e22c9117e103ea!8m2!3d44.8116328!4d-86.0561903?hl=en&authuser=0>`_.
* Understand the weather and learn about :ref:`eval`.

.. tip:: Pilots must have the phone photo or physical permit in hand when using any National Lakeshore land. 



`Rules and maps in PDF <parksitesjune22.pdf>`_

.. image:: images/empirebluffmap.png

.. image:: images/empirebluffmap1.png
  
Details
====================

Flying is limited to 5 gliders at a time. Carts may be used to transport gliders.


All flights at Empire Bluff must be initiated south of a point where the trail comes to the bluff edge. Take off is to be more than 15 feet (4.57 meters) from the trail without climbing vertically up or down the bluff face. All pilots landing on the beach below Empire Bluff are to exit via the beach north to Empire Beach or south to Esch Road. The face of the bluff is to be avoided and must not be climbed.

.. raw:: html

            <section id="motor-database">

                <p><a class="reference external"
                    href="https://docs.google.com/spreadsheets/d/1LonjmR18rfkfzixBVeWdExnEeoR8efkAnBFFbX_BITs/edit?usp=sharing">Edit
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
                        // the sheet ID is the ONLY change
                        // 2PACX-1vT9LtwnjCkJ_Rq1Gi00XFsjvjxtHq4AE3aMTzMTA99Po9OGJm6C8K4x6A0-1RtUPzt3WRpwCznpBSiQ (what I get when publishing to the web)
                        // 13TjBa0W4AJ3GwWZfhOYba3IDddCQI7ox6W3VpFw3wZY (what I get when sharing with others)
      
                        const spreadsheetId = "1LonjmR18rfkfzixBVeWdExnEeoR8efkAnBFFbX_BITs";
                        
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
================


Hang gliding
-----------------------------

.. raw:: html 

  <iframe width="560" height="315" src="https://www.youtube.com/embed/jy9-ap7Ijhc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Paragliding
----------------------

.. raw:: html 

  <iframe width="560" height="315" src="https://www.youtube.com/embed/CCY_Xii3b0E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>



Photos
==========================

tbd
