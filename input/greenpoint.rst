************************************************
Greenpoint
************************************************



Details
====================

`Edit or copy the database <https://docs.google.com/spreadsheets/d/13TjBa0W4AJ3GwWZfhOYba3IDddCQI7ox6W3VpFw3wZY/edit?usp=sharing>`_


.. raw:: html



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

         $('table').tablesorter({
                  widgets        : ['zebra', 'columns'],
                  usNumberFormat : false,
                  sortReset      : true,
                  sortRestart    : true
         });
         }

         function loadData() {
         // from https://docs.google.com/spreadsheets/d/1O1r8choAQuhgh6FGf203ebjBLAv3VeXi2KZuJlWuQi4/edit?usp=sharing
         const spreadsheetId = "1O1r8choAQuhgh6FGf203ebjBLAv3VeXi2KZuJlWuQi4";
         const range = "!A:M";
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



Photos
==========================

The campground is awesome. The ramp sucks and requires wire help. 

.. image:: images/greenpoint1.png


USHPA Greenpoint club factoids
======================================

Greenpoint Flyers Association (GFA) is an USHPA chapter. 

GFA membership requires buying a share of the GFA corporation. 

A person or family can only hold one share. 

Cost? Varies by the seller. 

How many total shares are there? Unknown. 

GFA supposedly has bylaws and a roster that must be filed with USHPA, but only shareholders can see those docs. 

GFA is run by a board of directors. Only shareholders can participate in elections.  

Website? No. 

Open forum or Facebook page? No. Invite only. They've been known to delete posts they don't like, so free speech does not apply. 

Paying flight dues does not make you a member. Your fee only entitles you to fly Greenpoint. It does not entitle you to vote or participate in meetings. 



