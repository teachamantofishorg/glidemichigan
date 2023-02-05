************************************************
Dune Climb
************************************************

Overview TBD

* Owner: National Park Service
* Fees: None.
* Permit: NPS issues one annual permit for all sites at the `Philip Hart Visitor Center <https://www.google.com/maps/place/Philip+A.+Hart+Visitor+Center/@44.8116366,-86.058379,17z/data=!3m1!4b1!4m5!3m4!1s0x881e1af9c6058f8f:0xf4e22c9117e103ea!8m2!3d44.8116328!4d-86.0561903?hl=en&authuser=0>`_.
* Understand the weather and learn about :ref:`eval`.
* `PDF Map <duneclimbmap.pdf>`_

.. image:: images/duneclimbmap.png

Details
=====================

Flying is limited to 5 gliders at a time. Hand-carry gliders only. 

Hang gliding or paragliding is allowed on the east face of the Dune Climb from November 1 to March 31 of each year. Activities will be limited to tμe sand areas of the dune that do not have vegetation. Landings will take place either on top of the Dune Climb or in the grass area below the Dune Climb.

.. raw:: html

            <section id="motor-database">

                <p><a class="reference external"
                    href="https://docs.google.com/spreadsheets/d/1YxBgLFgAPA1eecVj8pd3vcZd0Cz_Ptz4RYHWJPVGo7w/edit?usp=sharing">Edit
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
                        const spreadsheetId = "2PACX-1vSNaYvABybBsosn3Tu-77Q-tFsXB-V6zCsDx3zcKB4FP2J4hippyc9kjfU8PWaiGSZiEYYsS8N2p9cB";
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



Photos
=================================

tbd
