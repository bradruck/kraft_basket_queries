**Description -**

This automation runs two different Qubole/Hive queries concurrently.  They are launched using an ActiveBatch schedule
and upon successful conclusion, they then launch further Active Batch processes. There are two (2) inputs in the
form of dates give to the automation which are inserted into the Qubole/Hive queries as start and end dates. If both
the queries are completed successfully, the automation exits with a (0), indicating success. Otherwise, if the
queries do not finish the automation exits with a (1), indicating failure.

**Application Information -**

Required modules: <ul>
                  <li>main.py,
                  <li>automation_manager.py,
                  <li>qubole_manager.py,
                  <li>queries.py,
                  <li>config.ini
                  </ul>

Location:         <ul>
                  <li>Deployment -> 
                  <li>               
                  <li>Scheduled to run however ? sees fit on ActiveBatch
                  </ul>

Source Code:      <ul>
                  <li>
                  </ul>

LogFile Location: <ul>
                  <li>na, accomplished via ActiveBatch
                  </ul>

**Contact Information -**

Primary Users:    <ul>
                  <li>
                  </ul>

Lead Customer:    <ul>
                  <li>
                  </ul>

Lead Developer:   <ul>
                  <li>Bradley Ruck
                  </ul>

Date Launched:    <ul>
                  <li>September, 2018
                  </ul>
