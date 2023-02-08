************************************************
Greenpoint
************************************************

Overview TBD

Notes

The campground is awesome. 

The HG ramp is not self-launch friendly and usually requires wire help. 

The PG launch is a dune swale that is partly on neighboring property. Until there's an issue, launching to the West is no problem. GFA property only allows for a NW launch.


* Owner: Greenpoint Flyers Association
* Fees: Day, month, and yearly passes
* `GFA regulations <GreenpointRegulations.pdf>`_.
* Understand the weather and learn about :ref:`eval`.

.. image:: images/greenpointmap.png

Details
====================

.. raw:: html

            <section id="motor-database">

                <p><a class="reference external"
                    href="https://docs.google.com/spreadsheets/d/13TjBa0W4AJ3GwWZfhOYba3IDddCQI7ox6W3VpFw3wZY/edit?usp=sharing">Edit
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
                        const spreadsheetId = "13TjBa0W4AJ3GwWZfhOYba3IDddCQI7ox6W3VpFw3wZY";
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
==========================

.. image:: images/greenpoint1.png




