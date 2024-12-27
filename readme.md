## 1. users Collection
[
    { "_id": 1, "name": "John Doe", "mentor_id": 1 },
    { "_id": 2, "name": "Jane Smith", "mentor_id": 2 },
    { "_id": 3, "name": "Alice Johnson", "mentor_id": 3 },
    { "_id": 4, "name": "Bob Brown", "mentor_id": 1 },
    { "_id": 5, "name": "Charlie White", "mentor_id": 2 },
    { "_id": 6, "name": "David Green", "mentor_id": 3 },
    { "_id": 7, "name": "Ella Black", "mentor_id": 1 },
    { "_id": 8, "name": "Frank Gray", "mentor_id": 2 },
    { "_id": 9, "name": "Grace Blue", "mentor_id": 3 },
    { "_id": 10, "name": "Hank Red", "mentor_id": 1 }
]

## 2. codekata Collection

[
    { "_id": 1, "user_id": 1, "problems_solved": 50 },
    { "_id": 2, "user_id": 2, "problems_solved": 100 },
    { "_id": 3, "user_id": 3, "problems_solved": 150 },
    { "_id": 4, "user_id": 4, "problems_solved": 80 },
    { "_id": 5, "user_id": 5, "problems_solved": 70 },
    { "_id": 6, "user_id": 6, "problems_solved": 90 },
    { "_id": 7, "user_id": 7, "problems_solved": 60 },
    { "_id": 8, "user_id": 8, "problems_solved": 120 },
    { "_id": 9, "user_id": 9, "problems_solved": 110 },
    { "_id": 10, "user_id": 10, "problems_solved": 95 }
]

## 3. attendance Collection

[
    { "_id": 1, "user_id": 1, "date":"2020-10-15", "status": "Absent" },
    { "_id": 2, "user_id": 2, "date": "2020-10-16", "status": "Present" },
    { "_id": 3, "user_id": 3, "date": "2020-10-17", "status": "Absent" },
    { "_id": 4, "user_id": 4, "date": "2020-10-18", "status": "Present" },
    { "_id": 5, "user_id": 5, "date": "2020-10-19", "status": "Absent" },
    { "_id": 6, "user_id": 6, "date": "2020-10-20", "status": "Present" },
    { "_id": 7, "user_id": 7, "date": "2020-10-21", "status": "Absent" },
    { "_id": 8, "user_id": 8, "date": "2020-10-22", "status": "Present" },
    { "_id": 9, "user_id": 9, "date": "2020-10-23", "status": "Absent" },
    { "_id": 10, "user_id": 10, "date":"2020-10-24", "status": "Present" }
]
## 4. topics Collection
[
    { "_id": 1, "topic_name": "Intro to MongoDB", "date": "2020-10-05" },
    { "_id": 2, "topic_name": "MongoDB Queries", "date":"2020-10-06" },
    { "_id": 3, "topic_name": "Aggregation", "date":"2020-10-07" },
    { "_id": 4, "topic_name": "Schema Design", "date":"2020-10-08" },
    { "_id": 5, "topic_name": "Indexes", "date":"2020-10-09" },
    { "_id": 6, "topic_name": "Replication", "date":"2020-10-10" },
    { "_id": 7, "topic_name": "Sharding", "date":"2020-10-11" },
    { "_id": 8, "topic_name": "Transactions", "date":"2020-10-12" },
    { "_id": 9, "topic_name": "Performance Tuning", "date":"2020-10-13" },
    { "_id": 10, "topic_name": "Security", "date":"2020-10-14" }
]
## 5. tasks Collection
[
    { "_id": 1, "task_name": "Task 1", "topic_id": 1, "user_id": 1, "status": "Submitted" },
    { "_id": 2, "task_name": "Task 2", "topic_id": 2, "user_id": 2, "status": "Not Submitted" },
    { "_id": 3, "task_name": "Task 3", "topic_id": 3, "user_id": 3, "status": "Submitted" },
    { "_id": 4, "task_name": "Task 4", "topic_id": 4, "user_id": 4, "status": "Not Submitted" },
    { "_id": 5, "task_name": "Task 5", "topic_id": 5, "user_id": 5, "status": "Submitted" },
    { "_id": 6, "task_name": "Task 6", "topic_id": 6, "user_id": 6, "status": "Not Submitted" },
    { "_id": 7, "task_name": "Task 7", "topic_id": 7, "user_id": 7, "status": "Submitted" },
    { "_id": 8, "task_name": "Task 8", "topic_id": 8, "user_id": 8, "status": "Not Submitted" },
    { "_id": 9, "task_name": "Task 9", "topic_id": 9, "user_id": 9, "status": "Submitted" },
    { "_id": 10, "task_name": "Task 10", "topic_id": 10, "user_id": 10, "status": "Not Submitted" }
]
## 6. company_drives Collection
[
    { "_id": 1, "company_name": "Google", "drive_date": "2020-10-15" },
    { "_id": 2, "company_name": "Amazon", "drive_date": "2020-10-16" },
    { "_id": 3, "company_name": "Microsoft", "drive_date":"2020-10-17" },
    { "_id": 4, "company_name": "Facebook", "drive_date": "2020-10-18" },
    { "_id": 5, "company_name": "Apple", "drive_date":"2020-10-19" },
    { "_id": 6, "company_name": "Netflix", "drive_date":"2020-10-20" },
    { "_id": 7, "company_name": "Tesla", "drive_date":"2020-10-21" },
    { "_id": 8, "company_name": "Adobe", "drive_date":"2020-10-22" },
    { "_id": 9, "company_name": "Salesforce", "drive_date":"2020-10-23"},
    { "_id": 10, "company_name": "Intel", "drive_date":"2020-10-24"}
]
## 7. mentors Collection
[
    { "_id": 1, "mentor_name": "Ak ", "mentee_count": 10 },
    { "_id": 2, "mentor_name": "Sathis ", "mentee_count": 20 },
    { "_id": 3, "mentor_name": "guvi ", "mentee_count": 30 }
]


## ## Question and ans ## ##

## 1. Find all the topics and tasks which are taught in the month of October
// Topics taught in October
db.topics.find({
    date: {
        $gte:newdate("2020-10-01"),
        $lt:newdate("2020-11-01")
    }
});

// Tasks associated with topics in October
db.tasks.aggregate([
    {
        $lookup: {
            from: "topics",
            localField: "topic_id",
            foreignField: "_id",
            as: "topic_details"
        }
    },
    {
        $unwind: "$topic_details"
    },
    {
        $match: {
            "topic_details.date": {
                $gte:"2020-10-01",
                $lt: "2020-11-01"
            }
        }
    }
]);
## 2. Find all the company drives which appeared between 15 Oct 2020 and 31 Oct 2020

db.company_drives.find({
    drive_date: {
        $gte: "2020-10-15",
        $lte: "2020-10-31"
    }
});

## 3. Find all the company drives and students who appeared for the placement
db.company_drives.aggregate([
    {
        $lookup: {
            from: "users",
            localField: "_id",
            foreignField: "drive_id", // Assuming `users` contains a `drive_id` field
            as: "students"
        }
    }
]);
## 4. Find the number of problems solved by the user in Codekata
db.codekata.aggregate([
    {
        $group: {
            _id: "$user_id",
            total_problems_solved: { $sum: "$problems_solved" }
        }
    }
]);
## 5. Find all the mentors who have mentee count more than 15
db.mentors.find({
    mentee_count: { $gt: 15 }
});
## 6. Find the number of users who are absent and tasks are not submitted between 15 Oct 2020 and 31 Oct 2020
db.attendance.aggregate([
    {
        $match: {
            date: {
                $gte: "2020-10-15",
                $lte: "2020-10-31"
            },
            status: "Absent"
        }
    },
    {
        $lookup: {
            from: "tasks",
            localField: "user_id",
            foreignField: "user_id",
            as: "task_details"
        }
    },
    {
        $unwind: "$task_details"
    },
    {
        $match: {
            "task_details.status": "Not Submitted"
        }
    },
    {
        $group: {
            _id: null,
            total_users: { $sum: 1 }
        }
    }
]);# mongos-db
