# UAT Script

## Before Running
* Locate the creds.json folder inside of the repository and change the email address located inside to the appropriate email address
* Verify that VPN is turned on - otherwise you will be unable to access SSMS
* The GUI will say "Not Responding" - this is responding. It takes time to go through the many rows in each table.

-----

* This code does the following:
    * Pulls information from our DW and UAT data from both SSMS (DW) and Snowflake (UAT)
    * Extracts differences between the two datasets
    * Places differences between the two datasets in a dw_df (data from the DW) sheet & a uat_df (data from the UAT) sheet inside of the Deltas/Differences.xlsx file


# Differences.csv

<!-- <p>
  <img 
    src=Photos/colored_cells.png
  >
</p> -->

-----

# Questions?
* You can contact me via email or GitHub!
    * Email: emilyporter920@gmail.com
    * GitHub Profile: Emily Porter || https://www.github.com/emilyporter920 