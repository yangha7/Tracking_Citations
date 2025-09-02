# Tracking_Citations
A tool that tracks the information of citations for a group/project, based on the info from Google Scholar

1. The DIALS related publication list can be found and updated [here](https://docs.google.com/spreadsheets/d/1IEcGzhiAaroOhdZ282TDy2h2qpJWA9RFhiKGqZNgqOw/edit?gid=867462615#gid=867462615).
2. Save the list of Google Scholar links in urls.txt
3. Citation_by_year.ipynb scrapes citation numbers by year from Google Scholar. It obtains citation number per year for each individual paper, and saves them in a csv file in a database format. It is recommended to run the script locally through Jupyter notebook rather than on JupyterHub.
4. The csv file can be later processed in Microsoft PowerBi to visualize the results.
An example of the results looks like the following. You can click individual papers or years to see their contributions.

<details>
<summary>📊 View DIALS PDB Deposition Dashboard</summary>

[Click here to open the interactive dashboard](https://app.powerbi.com/view?r=eyJrIjoiZWQxYzQ3OGUtZGIwYS00NDZmLTk1YjctNDU1YmViNTI5ZDNjIiwidCI6IjM5NjU3M2NiLWYzNzgtNGI2OC05YmM4LTE1NzU1YzBjNTFmMyIsImMiOjZ9)

</details>

<img width="528" alt="image" src="https://github.com/user-attachments/assets/c9abb72b-302e-4d8b-8fc2-f0a2719a1442" />
