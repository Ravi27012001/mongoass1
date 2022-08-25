# mongoass1

<pre> db.employee.insertMany([{id:1,firstname:"john",lastname:"Doe",salary:"2500",department:"HR",lastCompany:"x",lastSalary:"1000",overallexp:"2",contactInfo:"8245455545",yearGrad:2016,gradestream:"CSE"},{id:2,firstname:"john",lastname:"Doe",salary:"3000",department:"HR",lastCompany:"x",lastSalary:"1000",overallexp:"2",contactInfo:"8245455545",yearGrad:2016,gradestream:"CSE"},{id:3,firstname:"suresh",lastname:"Doe",salary:"3500",department:"HR",lastCompany:"x",lastSalary:"1000",overallexp:"2",contactInfo:"8245455545",yearGrad:2016,gradestream:"Electrical"},{id:4,firstname:"mukesh",lastname:"Doe",salary:"4000",department:"HR",lastCompany:"x",lastSalary:"1000",overallexp:"2",contactInfo:"8245455545",yearGrad:2016,gradestream:"CSE"},{id:5,firstname:"Sao",lastname:"Doe",salary:"4500",department:"HR",lastCompany:"x",lastSalary:"1000",overallexp:"2",contactInfo:"8245455545",yearGrad:2016,gradestream:"CSE"},{id:6,firstname:"john",lastname:"Doe",salary:"5000",department:"HR",lastCompany:"x",lastSalary:"1000",overallexp:"2",contactInfo:"8245455545",yearGrad:2016,gradestream:"CSE"},{id:7,firstname:"john",lastname:"Doe",salary:"5500",department:"HR",lastCompany:"x",lastSalary:"1000",overallexp:"2",contactInfo:"8245455545",yearGrad:2016,gradestream:"CSE"}])
{
        "acknowledged" : true,
        "insertedIds" : [
                ObjectId("630766f9542ad84e76d2b9d7"),
                ObjectId("630766f9542ad84e76d2b9d8"),
                ObjectId("630766f9542ad84e76d2b9d9"),
                ObjectId("630766f9542ad84e76d2b9da"),
                ObjectId("630766f9542ad84e76d2b9db"),
                ObjectId("630766f9542ad84e76d2b9dc"),
                ObjectId("630766f9542ad84e76d2b9dd")
        ]
}
> db.employee.find().pretty()
{
        "_id" : ObjectId("630765e3542ad84e76d2b9d6"),
        "id" : 1,
        "firstname" : "john",
        "lastname" : "Doe",
        "salary" : "2500",
        "department" : "HR",
        "lastCompany" : "x",
        "lastSalary" : "1000",
        "overallexp" : "2",
        "contactInfo" : "8245455545",
        "yearGrad" : 2016,
        "gradestream" : "CSE"
}
{
        "_id" : ObjectId("630766f9542ad84e76d2b9d7"),
        "id" : 1,
        "firstname" : "john",
        "lastname" : "Doe",
        "salary" : "2500",
        "department" : "HR",
        "lastCompany" : "x",
        "lastSalary" : "1000",
        "overallexp" : "2",
        "contactInfo" : "8245455545",
        "yearGrad" : 2016,
        "gradestream" : "CSE"
}
{
        "_id" : ObjectId("630766f9542ad84e76d2b9d8"),
        "id" : 2,
        "firstname" : "john",
        "lastname" : "Doe",
        "salary" : "3000",
        "department" : "HR",
        "lastCompany" : "x",
        "lastSalary" : "1000",
        "overallexp" : "2",
        "contactInfo" : "8245455545",
        "yearGrad" : 2016,
        "gradestream" : "CSE"
}
{
        "_id" : ObjectId("630766f9542ad84e76d2b9d9"),
        "id" : 3,
        "firstname" : "suresh",
        "lastname" : "Doe",
        "salary" : "3500",
        "department" : "HR",
        "lastCompany" : "x",
        "lastSalary" : "1000",
        "overallexp" : "2",
        "contactInfo" : "8245455545",
        "yearGrad" : 2016,
        "gradestream" : "Electrical"
}
{
        "_id" : ObjectId("630766f9542ad84e76d2b9da"),
        "id" : 4,
        "firstname" : "mukesh",
        "lastname" : "Doe",
        "salary" : "4000",
        "department" : "HR",
        "lastCompany" : "x",
        "lastSalary" : "1000",
        "overallexp" : "2",
        "contactInfo" : "8245455545",
        "yearGrad" : 2016,
        "gradestream" : "CSE"
}
{
        "_id" : ObjectId("630766f9542ad84e76d2b9db"),
        "id" : 5,
        "firstname" : "Sao",
        "lastname" : "Doe",
        "salary" : "4500",
        "department" : "HR",
        "lastCompany" : "x",
        "lastSalary" : "1000",
        "overallexp" : "2",
        "contactInfo" : "8245455545",
        "yearGrad" : 2016,
        "gradestream" : "CSE"
}
{
        "_id" : ObjectId("630766f9542ad84e76d2b9dc"),
        "id" : 6,
        "firstname" : "john",
        "lastname" : "Doe",
        "salary" : "5000",
        "department" : "HR",
        "lastCompany" : "x",
        "lastSalary" : "1000",
        "overallexp" : "2",
        "contactInfo" : "8245455545",
        "yearGrad" : 2016,
        "gradestream" : "CSE"
}
{
        "_id" : ObjectId("630766f9542ad84e76d2b9dd"),
        "id" : 7,
        "firstname" : "john",
        "lastname" : "Doe",
        "salary" : "5500",
        "department" : "HR",
        "lastCompany" : "x",
        "lastSalary" : "1000",
        "overallexp" : "2",
        "contactInfo" : "8245455545",
        "yearGrad" : 2016,
        "gradestream" : "CSE"
}
</pre>
>
