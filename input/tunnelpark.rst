************************************************
Tunnel Park
************************************************

TBD 

Paragliders have flown there in the winter. May be too crowded in the summer. 

Details
======================

TBD

.. raw:: html

            <section id="motor-database">

                <p><a class="reference external"
                    href="https://docs.google.com/spreadsheets/d/1whH1AtSidc4EK0SP6srEKr8JdlUwjfqVcTtDxGWDFS4/edit?usp=sharing">Edit
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
      

                        const spreadsheetId = "1vTieHQPqpnuyOHje67XEawFF44M0PsVkezllldgizABI0SQeTEMeg_Qc8M3eN1x1k2AsVF0TZUaL4HN";
                        
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
---------------------------

tbd
