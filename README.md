# Data-Engineering-project
The startup Sparkify wants to examine the information they've been gathering on songs and user behavior on their brand-new music streaming service. The analytics team is very curious to know which music users are listening to. They now lack a simple means to query their data, which is stored in directories containing JSON logs on user activity on the app and JSON information on the songs in their app.  A Spark ETL Pipeline was developed, which reads the data kept in S3 and enables Sparkify to interpret and analyze their data in a distributed manner.

# Data
Song data: s3://udacity-dend/song_data
Log data: s3://udacity-dend/log_data
A portion of actual data from the Million Song Dataset makes up the first dataset. Each file is in JSON format and includes metadata about a particular song and its artist. The first three letters of each song's track ID are used to divide the files into groups. Here are the filepaths to two of the dataset's files as an illustration.
The second dataset comprises of JSON-formatted log files that this event simulator created using the songs in the first dataset. Based on configuration parameters, these imitate the app activity logs of a hypothetical music streaming app.
