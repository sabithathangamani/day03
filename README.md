# day03
JSON
1.For the given JSON iterate over all for loops (for, for in)

var arr = [ {
      "id": 1,
      "first_name": "Robert",
      "last_name": "Schwartz",
      "email": "rob23@gmail.com"
    },
    {
      "id": 2,
      "first_name": "Lucy",
      "last_name": "Ballmer",
      "email": "lucyb56@gmail.com"
    }];
Using For Loop:    
for (var i=0;i<arr.length;i++){
var result=arr[i]
console.log(result.id)
console.log(result.last_name)}

Using For in Loop:
for(var b in result)
{console.log(b+" "+result[b])
}


2.Create your own resume data in JSON format
let resume={
    "Basics": {
      "Name": "Sabitha T",
      "email": "sabithathangamani@gmail.com",
      "Phone": "9080881197",
      "Qualification": "B.E"},
    "Location": {
        "address": "159,East Street,Anna nagar",
        "city": "Chennai",
        "postalCode": "600030",
        "state": "Tamilnadu",
        "country": "India"
      },
      
   
    "Work": 
      {
        "company": "Mphasis",
        "Role": "DBA",      
        "summary": "Worked on Oracle databases and Mainframe DB2 databases",
      },
    
    "Education": 
      {
        "institution": "Arunai Engineering College",
        "department": "ECE",
      },
    
    "Skills": 
      {
        "name": "Oracle 11gR2,10g,9i,SQLserver2005 and 2008",
        "level": "beginer",
        "project": 
          "Banking Project"
        
      },
    
    "Languages": 
      {
        "language": "Tamil,Enlish",
      }
    
    
}
  for (var b in resume){
       console.log(b,'\n',resume[b])
   
        }























  
