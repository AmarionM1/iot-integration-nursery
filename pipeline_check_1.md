# Data Pipeline Check #1 – Nursery

## File 1: batch101.csv

**1. What information does this file record?**

This file shows who went into the nursery rooms, what time they went in, the date, and whether they were a nurse, doctor, parent, or patient.

**2. What kind of device do you think produced this file, and what in the data makes you think so?**

I think this came from some type of badge scanner or door access system because it keeps track of people going into different rooms.

**3. What identifies one record?**

Each row is one record. The date, time, room number, and person ID help tell each record apart.

**4. How are the fields represented?**

The data is organized into rows and columns. Each column has a name like Time, Date, Room, PersonID, and PersonType.

**5. How many records are there?**

There are 40 records.

**6. What do you notice about how the device actually collects and stores data?**

I noticed that the times are different for each record. So I think the device only records something when somebody accesses a room instead of recording at a set time.

**7. What are the advantages and disadvantages of this data format?**

One advantage of CSV is that it's simple and easy to read. You can also open it in Excel. One disadvantage is that it doesn't work as well with more complicated data.

## File 2: stream101.json

**1. What information does this file record?**

This file records the temperature of the nursery rooms and whether the doors are open or closed. It also shows the room number and time.

**2. What kind of device do you think produced this file, and what in the data makes you think so?**

I think this came from a room monitoring system because it's keeping track of the temperature and door status in different rooms.

**3. What identifies one record?**

Each record is a reading from a certain room at a certain time. The room number and date/time help identify it.

**4. How are the fields represented?**

The data is stored using key-value pairs. Each reading has things like dateTime, roomNumber, roomTempF, and doorStatus.

**5. How many records are there?**

There are 36 records.

**6. What do you notice about how the device actually collects and stores data?**

I noticed that the device takes readings every 30 minutes for four different rooms. It records the temperature and if the door is open or closed.

**7. What are the advantages and disadvantages of this data format?**

One advantage of JSON is that it keeps the data organized and is easy for programs to use. One disadvantage is that it can get confusing to read when there's a lot of data.

## File 3: feed101.xml

**1. What information does this file record?**

This file records the newborn patients' heart rate, breathing rate, and body temperature. It also shows the patient ID, date, and time.

**2. What kind of device do you think produced this file, and what in the data makes you think so?**

I think this came from a patient monitoring device because it records different vital signs like heart rate, breathing rate, and temperature.

**3. What identifies one record?**

Each record is one patient's vital signs at a certain time. The patient ID, date, and time help identify each record.

**4. How are the fields represented?**

The data uses XML tags to separate the information. Each tag tells you what the data is, like heartRate, breathingRate, or temperature.

**5. How many records are there?**

There are 196 records.

**6. What do you notice about how the device actually collects and stores data?**

I noticed that the device records information every five minutes for four patients. It keeps track of their vital signs throughout the day.

**7. What are the advantages and disadvantages of this data format?**

One advantage of XML is that the tags make it easy to understand what each piece of data means. One disadvantage is that it uses a lot of extra lines and can be harder to work with compared to CSV or JSON.
