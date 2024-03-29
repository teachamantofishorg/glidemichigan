************************************************
Pyramid Point
************************************************

Overview TBD

* Owner: National Park Service
* Fees: None.
* Permit: NPS issues one annual permit for all sites at the `Philip Hart Visitor Center <https://www.google.com/maps/place/Philip+A.+Hart+Visitor+Center/@44.8116366,-86.058379,17z/data=!3m1!4b1!4m5!3m4!1s0x881e1af9c6058f8f:0xf4e22c9117e103ea!8m2!3d44.8116328!4d-86.0561903?hl=en&authuser=0>`_.
* Understand the weather and learn about :ref:`eval`.

.. tip:: Pilots must have the phone photo or physical permit in hand when using any National Lakeshore land. 


`Rules and maps in PDF <parksitesjune22.pdf>`_

.. image:: images/pyramidpointmap.png

.. image:: images/pyramidpointmap1.png

.. image:: images/pyramidpointmap2.png

.. image:: images/pyramidpointmap3.png

Details
====================

Flying is limited to 5 gliders at a time. Carts may be used to transport gliders.

All flights at Pyramid Point will be initiated from the blowout at the top of the bluff. All pilots landing on the beach below Pyramid Point will exit the area via the trail that ends at the east end of the dune area. The face of the bluff will be avoided and will not be climbed. Pilots may also land in the field east of the Klett Farm or in the field that is south of Baker Road and east of Port Oneida Road.

======================

TBD

.. raw:: html

            <section id="motor-database">

                <p><a class="reference external"
                    href="https://docs.google.com/spreadsheets/d/19ylKzbffOvfU3_kvy9z1Db_VSyAP5v7IBz_97-KSEdw/edit?usp=sharing">Edit
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
                        const spreadsheetId = "1rKDSa2vtXpZv6oLBb6BPHeFEZU1INiJS1_VSzBNVE00";  
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
