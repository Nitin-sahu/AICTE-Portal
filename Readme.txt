

correct form on 29-06-2022
// for showing the logged in username  in a web page USING LIQUID CODE
<a> {{% user.firstname %%}}

// sending json data in as request Using JAVASCRIPT XHRHTTPRequest() mehtod

let xhr = new XMLHttpRequest();
let url=https://prod-26.centralindia.logic.azure.com:443/workflows/d4217add8aa1445789310008f498131f/triggers/manual/paths/invoke?api-version=2016-06-01&sp=%2Ftriggers%2Fmanual%2Frun&sv=1.0&sig=oaZpTzZj_0vNGZSMuL-Owje9-5mxQ7DtkSzVCt0Lo78;

xhr.open('GET',url,true);
	

xhr.onload=function()
{
 
let xmldata=xhr.responseXML;
let textdata = xhr.responseText;

let data=JSON.parse(textdata);
console.log(xmldata);
console.log(textdata);
console.log(data);
}
xhr.send();


// converting data  present in variable recived via  html form  to  JAVASCRIPT JASON ,(key:value)pair  for sending to  automate's unique http url's body
{
	"AICTE": [{"Permanent id": "Pid"},
		{"Institue id": "INid"},
		{"Institue Region": "IRid"},
		{"Institue District": "IDid"},
		{"Name of Organization": "NOid"},
		{"Mobile Number": "Nuid "},
		{"Email id": "Eid"}

	]
}


---javascript---


//JAVASCRIPT FUNCTION  to input values Using HTML ID in JAVASCRIPT variables on clicking  HTML submit button 


function my_button_click_handler()
{
alert(' state data  submitted  ');

var istate = document.getElementById("istate").value;
//fetch data from variable to element

var Pid = document.getElementById("Pid").value;
document.getElementById("demo").innerHTML= "The value is : " +Pid;
var INid = document.getElementById("INid").value;
var IRid = document.getElementById("IRid").value;

var IDid = document.getElementById("IDid").value;
var NOid = document.getElementById("NOid").value;
var Nid = document.getElementById("Nid").value;
var Nuid = document.getElementById("NUid").value;
var Eid = document.getElementById("Eid").value;
var Syullabusid = document.getElementById("Syllabusid").value;


//JAVASCRIPT STRINGY funcction() to convert JS variable to JS key value pair 

JSON.stringify({"Permanent Id":"Pid","Institue Name ":"INid","Institue Region":"IRid","Institue State":"istate","Institue District" :"IDdiv","Name of Organization":"Noid","Name":"Number","NUid","Email":"EMid"}

})
function favTutorial() {
   var mylist = document.getElementById("myList");
   
   
   var x=mylist.options[mylist.selectedIndex].value;
   
   if(x== "0")
   {

//Javascript's JQUERY's HIDE and DELETE functin to show HTML's ID ELEMENT
       
                 $("#state").hide();
                  $("#IRdiv").hide();
             $("#INdiv").hide();
              $("#IDDiv").hide();

                   $("#ID").hide();
              $("#Nodiv").hide();
    
     }
   if(x== "1")
   {
         alert('jquery run');
         $("#state").show();
         
              $("#INdiv").show();
                  $("#IRdiv").show();
         
            
              $("#IDDiv").show();

              $("#ID").show();
              $("#Nodiv").hide();
         }
   
   
   if(x=="2")
   {
          $("#state").show();
                  $("#IRdiv").hide();
         
              $("#INdiv").hide();
              $("#IDDiv").hide();
              $("#ID").hide();
              $("#Nodiv").show();

   
   }
   
   if(x== "3")
   {
                  $("#state").show();
                  $("#IRdiv").hide();
         
              $("#INdiv").hide();
              $("#IDDiv").hide();
              $("#ID").hide();
              $("#Nodiv").hide();

   }
   
   if(x== "4")
   {
                 $("#state").show();
                  $("#IRdiv").hide();
             $("#INdiv").hide();
              $("#IDDiv").hide();

                   $("#ID").hide();
              $("#Nodiv").hide();

   

   }
   
  

      
}

   
   
    

--------[

function my_button_click_handler()
{
alert(' state data  submitted  ');

var istate = document.getElementById("istate").value;
//fetch data from variable to element

var Pid = document.getElementById("Pid").value;
document.getElementById("demo").innerHTML= "The value is : " +Pid;
var INid = document.getElementById("INid").value;
var IRid = document.getElementById("IRid").value;

var IDid = document.getElementById("IDid").value;
var NOid = document.getElementById("NOid").value;
var Nid = document.getElementById("Nid").value;
var Nuid = document.getElementById("NUid").value;
var Eid = document.getElementById("Eid").value;
var Syullabusid = document.getElementById("Syllabusid").value;

{"Permanent Id":"Pid","Institue Name ":"INid","Institue Region":"IRid","Institue State":"istate","Institue District" :"IDdiv","Name of Organization":"Noid","Name":"Number","NUid","Email":"EMid"}

}
function favTutorial() {
   var mylist = document.getElementById("myList");
   
   
   var x=mylist.options[mylist.selectedIndex].value;
   
   if(x== "0")
   {
       
                 $("#state").hide();
                  $("#IRdiv").hide();
             $("#INdiv").hide();
              $("#IDDiv").hide();

                   $("#ID").hide();
              $("#Nodiv").hide();
    
     }
   if(x== "1")
   {
         alert('jquery run');
         $("#state").show();
         
              $("#INdiv").show();
                  $("#IRdiv").show();
         
            
              $("#IDDiv").show();

              $("#ID").show();
              $("#Nodiv").hide();
         }
   
   
   if(x=="2")
   {
          $("#state").show();
                  $("#IRdiv").hide();
         
              $("#INdiv").hide();
              $("#IDDiv").hide();
              $("#ID").hide();
              $("#Nodiv").show();

   
   }
   
   if(x== "3")
   {
                  $("#state").show();
                  $("#IRdiv").hide();
         
              $("#INdiv").hide();
              $("#IDDiv").hide();
              $("#ID").hide();
              $("#Nodiv").hide();

   }
   
   if(x== "4")
   {
                 $("#state").show();
                  $("#IRdiv").hide();
             $("#INdiv").hide();
              $("#IDDiv").hide();

                   $("#ID").hide();
              $("#Nodiv").hide();

   

   }
   
  

      
}

   
   
    

-------------

function my_button_click_handler()
{
alert(' state data  submitted  ');

var istate = document.getElementById("istate").value;


//fetch data from variable to element
document.getElementById("demo").innerHTML= "The value is : " +istate;

}
function favTutorial() {
   var mylist = document.getElementById("myList");
   
   
   var x=mylist.options[mylist.selectedIndex].value;
   
   if(x== "0")
   {
       
                 $("#state").hide();
                  $("#IRdiv").hide();
             $("#INdiv").hide();
              $("#IDDiv").hide();

                   $("#ID").hide();
              $("#Nodiv").hide();
    
     }
   if(x== "1")
   {
         alert('jquery run');
         $("#state").show();
         
              $("#INdiv").show();
                  $("#IRdiv").show();
         
            
              $("#IDDiv").show();

              $("#ID").show();
              $("#Nodiv").hide();
         }
   
   
   if(x=="2")
   {
          $("#state").show();
                  $("#IRdiv").hide();
         
              $("#INdiv").hide();
              $("#IDDiv").hide();
              $("#ID").hide();
              $("#Nodiv").show();

   
   }
   
   if(x== "3")
   {
                  $("#state").show();
                  $("#IRdiv").hide();
         
              $("#INdiv").hide();
              $("#IDDiv").hide();
              $("#ID").hide();
              $("#Nodiv").hide();

   }
   
   if(x== "4")
   {
                 $("#state").show();
                  $("#IRdiv").hide();
             $("#INdiv").hide();
              $("#IDDiv").hide();

                   $("#ID").hide();
              $("#Nodiv").hide();

   

   }
   
  

      
}

   
   
    



--------------------
function favTutorial() {
   var mylist = document.getElementById("myList");
   
   
   var x=mylist.options[mylist.selectedIndex].value;
   
   if(x== "0")
   {

    
     }
   if(x== "1")
   {
         alert('jquery run');
         $("#state").show();
         
              $("#INdiv").show();
                  $("#IRdiv").show();
         
            
              $("#IDDiv").show();

              $("#ID").show();
              $("#Nodiv").hide();
         }
   
   
   if(x=="2")
   {
          $("#state").show();
                  $("#IRdiv").hide();
         
              $("#INdiv").hide();
              $("#IDDiv").hide();
              $("#ID").hide();
              $("#Nodiv").show();

   
   }
   
   if(x== "3")
   {
                  $("#state").show();
                  $("#IRdiv").hide();
         
              $("#INdiv").hide();
              $("#IDDiv").hide();
              $("#ID").hide();
              $("#Nodiv").hide();

   }
   
   if(x== "4")
   {
                 $("#state").show();
                  $("#IRdiv").hide();
             $("#INdiv").hide();
              $("#IDDiv").hide();

                   $("#ID").hide();
              $("#Nodiv").hide();

   

   }
   
  

      
}

   
   
    
-------------------------------------------------------
---html---


//Bootsraps's class col and row class to show grid.
<form method="POST">
<div class="container-fluid">
  <div class="header_main">
    <div class="logo"><img src="https://www.aicte-india.org/sites/default/files/logo_new.png"></div>
    <div class="left_tabs">
      <div class="homelogo"><img src="https://img.icons8.com/material-rounded/344/home.png" style="height: 79px;"><a href="window.location.href='~/new-page;">Home</a></div>
      <div class="text"><span style="display: inherit; font-weight: 400; color: #696969;">Welcome</span> <a style="display: inherit; font-family: poppins; font-weight: 700; color: #005377;"> {{%user.firstname%}}</a></div>
      <div class="loginpic"><img src="https://cdn-icons-png.flaticon.com/128/149/149071.png" style="height: 60px;"></div>
    </div>
  </div>
  <div class="task_title" style="color: #3A3A3A; font-weight: 700; font-size: 24px; line-height: 36px; padding: 10px;">
    Proposals for New Course Nomenclatures for APH 2022-23
  </div>
  <div class="task_container">
    <div><span class="task_label" style="color: #005377; font-weight: 700; padding: 10px;">Basic Information</span></div>
    <hr><br>
    <div class="row">
      <div class="col-md-6">
        <div><span>Institute</span></div>
      </div>
      <div class="col-md-6">
        <select id="myList" onchange="favTutorial()">
            <option value="0"> ---Choose Option--- </option>
            <option value="1">AICTE Approved Autonomous Institute </option>
            <option value="2"> University </option>
            <option value="3"> State DTE </option>
            <option value="4"> State Higher Education Department </option>
          </select>
      </div>
    </div><br>
    <div id="IDDiv" class="row" style="display: none;">
      <div class="col-md-6">
        <div><label for="PI ">Permanent Id*:</label>
          <h6>/* Note* In Case if AICTE permanent ID is not available please enter (AICTE Current Application ID) */</h6>
        </div>
      </div>
      <div class="col-md-4">
        <div><span><input type="text "  placeholder="AICTE Permanent Id" name="fname "><a>Click here</a> to get permanent/current Application ID. 
               </span></div>
      </div>
      <div class="col-md-2">
        <div><span><button type="button" style="background: #005377; color: #FFFFFF;">Check</button></span></div>
      </div>
      </div>

      <div id="INdiv" class="row">
        <div class="col-md-6">
          <div><span><label for="ID ">Institute Name *:</label></span></div>
        </div>
        <div class="col-md-6">
          <div><span><input type="text " placeholder="Enter AICTE ID and data will populate automatic" name="fname "></span></div>
        </div>
      </div>
      
      <br>
      <div class="row" id="IRdiv">
        <div class="col-md-6">
          <div><span>Institute Region*</span></div>
        </div>
        <div class="col-md-6">
          <div><span><input type="text " placeholder="Enter AICTE ID and data will populate automatic" name="fname "></span></div>
        </div>
      </div>
      <br>

      <div id="state" class="row">
        <div class="col-md-6">
          <div><span><label for="ID ">Institute State/UT's *:</label></span></div>
        </div>
        <div class="col-md-6">
          <div><span><input type="text " placeholder="Enter AICTE ID and data will populate automatic" name="fname "></span></div>
        </div>
      </div>
      <br>
      <div class="row" id="ID">
        <div class="col-md-6">
          <div><span><label for="ID ">Institute District *:</label></span></div>
        </div>
        <div class="col-md-6">
          <div><span><input type="text " placeholder="Enter AICTE ID and data will populate automatic" name="fname "></span></div>
        </div>
      </div>
  
      <div id="Nodiv" class="row" style="display: none;">
      <div class="col-md-6">
        <div><span><label for="IN ">Name of Organization/University/Department*:</label></span></div>
      </div>
      <div class="col-md-6">
        <div><span><input type="text " id="org" placeholder="Enter Organization/Department" name="fname "></span></div>
      </div><br><br>
     
    </div>

    
  </div>
</div></form><br><br>
<!-- o -->
<div class="task_container2"><br>
  <div><span class="task_label" style="color: #005377; font-weight: 700; padding: 10px;">Details of Contact Person for any clarification regarding Syllabus / Course name :</span></div>
  <hr><br>
  <div class="row" id="Namediv">
    <div class="col-md-6">
      <div><label for="NP ">Name of Person*:</label></div>
    </div>
    <div class="col-md-6">
      <div><span><input type="text " id="name" placeholder="Please Enter your Name" name="fname "><br><br></span></div>
    </div><br>
  </div>
  <div class="row" id="MobileDiv">
    <div class="col-md-6"><br>
      <div><span><label for="MN "> Mobile Number*:</label></span></div>
    </div>
    <div class="col-md-6">
      <div><span><input id="number" type="number " placeholder="Please Enter your Number" name="fname "></span></div>
    </div><br>
  </div>
  <div class="row" id="Emailidiv">
    <div class="col-md-6"><br>
      <div><label for="EI ">Email Id*:</label></div>
    </div>
    <div class="col-md-6">
      <div><span><input type="email " placeholder="Please Enter your EMAIL" name="fname "></span></div>
    </div>
  </div><br><br>
  <div class="row" id="syllabysdiv">
    <div class="col-md-6">
      <div><label for="Ps ">Please upload copy of syllabus*:</label></div>
    </div>
    <div class="col-md-6">
      <div><span><label for="myfile" style="background: #005377; color: #FFFFFF;"></label><input type="file" placeholder="Please Enter your Name" id="myfile" name="myfile" multiple=""><br><br></span></div>
    </div>
  </div><br><br>
</div>


<div class="btn"><button type="Submit" onclick="my_button_click_handler()">Press here</button> </div>
//Task Nomencalute customized form using html, css

updated
<script>

function favTutorial() {
var mylist = document.getElementById("myList");
//document.getElementById("favourite").value = 

var x=mylist.options[mylist.selectedIndex].value;

if(x== "1")
{
    document.getElementById("University").style.display="none";
    document.getElementById("State DTE").style.display="none";
    document.getElementById("State Higher Education Department").style.display="none";
}

if(x== "2")
{
    document.getElementById("note").style.display="none";
    document.getElementById("State DTE").style.display="none";
    document.getElementById("State Higher Education Department").style.display="none";
}

if(x== "3")
{
    document.getElementById("note").style.display="none";
    document.getElementById("University").style.display="none";
    document.getElementById("State Higher Education Department").style.display="none";
}

if(x== "4")
{
    document.getElementById("note").style.display="none";
    document.getElementById("University").style.display="none";
    document.getElementById("State DTE").style.display="none";
}

}

</script>

//HTML 'S DIV CONTIANER AND IMG TAGS for creating form layout
<div class="container-fluid">

    <div class="header_main">

        <div class="logo">
            <img src="https://www.aicte-india.org/sites/default/files/logo_new.png">
        </div>

        <div class="left_tabs">

            <div class="homelogo">
                <img src="https://img.icons8.com/material-rounded/344/home.png" style="
    height:79px;">
                <a href="window.location.href='~/new-page;">Home</a>
            </div>

            <div class="text">

                <span style="display:inherit; font-weight:400;color:#696969;">Welcome</span>

                <span style="display:inherit;font-family: poppins;font-weight:700;color:#005377;">Yogesh Chauhan</span>
            </div>

            <div class="loginpic">
                <img src="https://cdn-icons-png.flaticon.com/128/149/149071.png" style="
    height: 60px;">
            </div>

        </div>

    </div>



    <div class=" task_title " style="color: #3A3A3A; font-weight:700;font-size:24px;line-height:36px;padding: 10px">
        Proposals for New Course Nomenclatures for APH 2022-23
    </div>

    <div class="task_container ">
        <div>
            <span class="task_label " style="color: #005377; font-weight:700;padding: 10px">Basic Information</span>

        </div>
        <hr>
        <br>
        <div class="row">
            <div class="col-md-6 ">
                <div>
                    <span>Institute</span>
                </div>
            </div>
            <div class="col-md-6 ">
                <!-- <div>
                    <select id="myList" onchange="favTutorial()">
                        <option id="option1">AICTE Approved Autonomous Institute</option>
                        <option id="option2">University</option>
                        <option id="option3">State DTE</option>
                        <option id="option4">State Higher Education Department</option>
                    </select>
                </div> -->


                <form>
//HTML's  select to drop down 

            <select id = "myList" onchange = "favTutorial()" >
            <option> ---Choose Option--- </option>
            <option value = "1">AICTE Approved Autonomous Institute </option>
            <option value ="2"> University  </option>
            <option value="3"> State DTE  </option>
            <option value="4"> State Higher Education Department </option>
            </select>


            <p> Your selected tutorial site is: 

            <input type = "value" id = "favourite" size = "20" </p>
            </form>

                

            </div>
        </div>

        <br>
        
        <div class="row " id="Aicte">
            <div class="col-md-6 ">
                <div>
                    <label for="PI ">Permanent Id*:</label>
                    <h6>/* Note* In Case if AICTE permanent ID is not available please enter (AICTE Current Application ID) */</h6>
                </div>
            </div>
            <div class="col-md-4 ">
                <div>
                    <span>
                        <input type="text " id="PI " name="fname ">
                <a>Click here</a> to get permanent/current Application ID. 
                    </span>
                </div>
            </div>
            <div class="col-md-2 ">
                <div>
                    <span>
 
                    <button type="button" style="background: #005377;color: #FFFFFF;">Check</button>
                    </span>
                </div>
            </div>
        </div>
        <br>
        <div class="row ">

            <div class="col-md-6 ">
                <div>
                    <label for="IN ">Institute Name*:</label>
                </div>
            </div>

            <div class="col-md-6 ">
                <div>
                    <span>
                        <input type="text " id="IN " name="fname ">
                    </span>
                </div>
            </div>
        </div>
        <br>
        <div class="row ">
            <div class="col-md-6 ">
                <div>
                    <span>
                        <label for="He ">Institute Region*:</label>
                    </span>
                </div>
            </div>
            <div class="col-md-6 ">
                <div>
                    <span>
                        <input type="text " id="He " name="fname ">
                    </span>
                </div>
            </div>
        </div>
        <br>

        <div class="row ">
            <div class="col-md-6 ">
                <div>
                    <span>Institute State/UT*</span>
                </div>
            </div>
            <div class="col-md-6 ">
                <div>
                    <span>
                        <input type="text " id="fname " name="fname ">
                    </span>
                </div>
            </div>
        </div>
        <br>

        <div class="row ">
            <div class="col-md-6 ">
                <div>
                    <span>
                        <label for="ID ">Institute District *:</label>
                    </span>
                </div>
            </div>
            <div class="col-md-6 ">
                <div>
                    <span>
                        <input type="text " id="ID " name="fname ">
                    </span>
                </div>
            </div>

        </div>


    
        <div class="row " id="University">

        <!-- <div class="col-md-6 "> -->
        <!-- <div class="row "> -->

                    <div class="col-md-6 ">
                        <div>
                        <label for="IN ">Name of Organization/University/Department*:</label>
                        </div>
                    </div>

                <div class="col-md-6 ">
                    <div>
                        <span>
                        <input type="text " id="IN " name="fname ">
                        </span>
                        </div>
                    </div>

        </div>

        <br>
        <div class="row ">
            <div class="col-md-6 ">
                <div>
                    <span>
                        <label for="He ">Institute State/UT*:</label>
                    </span>
                </div>
            </div>

            <div class="col-md-6 ">
                <div>
                    <span>
                        <input type="text " id="He " name="fname ">
                    </span>
                </div>
            </div>
        </div>

        <br>
        <br>

        
        <div class="row " id="State DTE">
            <div class="col-md-6 ">
                <div>
                    <span>
                        <label for="He ">Institute State/UT*:</label>
                    </span>
                </div>
            </div>
            <div class="col-md-6 ">
                <div>
                    <span>
                        <input type="text " id="He " name="fname ">
                    </span>
                </div>
            </div>
        </div>

        
        <div class="row " id="State Highter Education Department">
            <div class="col-md-6 ">
                <div>
                    <span>
                        <label for="He ">Institute State/UT*:</label>
                    </span>
                </div>
            </div>
            <div class="col-md-6 ">
                <div>
                    <span>
                        <input type="text " id="He " name="fname ">
                    </span>
                </div>
            </div>
        </div>

    </div>
<!-- o -->
    <div class="task_container2 ">
        <div>
            <span class="task_label " style="color: #005377; font-weight:700;padding: 10px">Details of Contact Person for any clarification regarding Syllabus / Course name :</span>

        </div>
        <hr>
        <br>
        <div class="row ">
            <div class="col-md-6 ">
                <div>
                    <label for="NP ">Name of Person*:</label>
                </div>
            </div>
            <div class="col-md-6 ">
                <div>
                    <span>
                        <input type="text " id="NP " name="fname "><br>
                        <br>
                        
                    </span>
                </div>
            </div>

            <br>
        </div>

        <div class="row ">
            <div class="col-md-6 ">
                <br>
                <div>
                    <span>
                        <label for="MN "> Mobile Number*:</label>
                    </span>
                </div>
            </div>
            <div class="col-md-6 ">
                <div>
                    <span>
                        <input type="number " id="MN " name="fname ">
                    </span>
                </div>
            </div>
            <br>
        </div>

        <div class="row ">
            <div class="col-md-6 ">
                <br>
                <div>
                    <label for="EI ">Email Id*:</label>
                </div>

            </div>
            <div class="col-md-6 ">
                <div>
                    <span>
                        <input type="email " id="EI " name="fname ">
                    </span>
                </div>
            </div>
        </div>

        <br><br>

        <div class="row ">
            <div class="col-md-6 ">

                <div>
                    <label for="Ps ">Please upload copy of syllabus*:</label>
                </div>

            </div>

            <div class="col-md-6 ">
                <div>
                    <span>
            
                    <label for="myfile" style="background: #005377;color: #FFFFFF;"></label>
                    <input type="file" id="myfile" name="myfile" multiple=""><br><br>
                "&gt;
                </span>

                </div>
            </div>
        </div> -->

        <br>
        <br>

    <!-- </div>
    <div class="row">
        <div class="col-md-6"></div>
        <div class="col-md-6">
            <div>
                <div class="submit">
                    <a>
                        Submit</a>

                </div>
            </div>
        </div>
    </div> 
</div>



==================
<div class="container-fluid">

    <div class="header_main">

        <div class="logo">
            <img src="https://www.aicte-india.org/sites/default/files/logo_new.png">
        </div>

        <div class="left_tabs">

            <div class="homelogo">
                <img src="https://img.icons8.com/material-rounded/344/home.png" style="
    height:79px;">  
                <a href="window.location.href='~/new-page;">Home</a>
            </div>

            <div class="text">

                <span style="display:inherit; font-weight:400;color:#696969;">Welcome</span>

                <span style="display:inherit;font-family: poppins;font-weight:700;color:#005377;">Yogesh Chauhan</span>
            </div>

            <div class="loginpic">
                <img src="https://cdn-icons-png.flaticon.com/128/149/149071.png" style="
    height: 60px;">
            </div>

        </div>

    </div>



    <div class=" task_title " style="color: #3A3A3A; font-weight:700;font-size:24px;line-height:36px;padding: 10px">
        Proposals for New Course Nomenclatures for APH 2022-23
    </div>

    <div class="task_container ">
        <div>
            <span class="task_label " style="color: #005377; font-weight:700;padding: 10px">Basic Information</span>

        </div>
        <hr>
        <br>
        <div class="row">
            <div class="col-md-6 ">
                <div>
                    <span>Institute</span>
                </div>
            </div>
            <div class="col-md-6 ">
                <div>
                    <select class="input-wid " name=" " id="input_box">
                        <option id="option1">AICTE Approved Autonomous Institute</option>
                        <option id="option2">University</option>
                        <option id="option3">State DTE</option>
                        <option id="option4">State Higher Education Department</option>
                    </select>
                </div>

            </div>
        </div>

        <br>
        <div class="row ">
            <div class="col-md-6 ">
                <div>
                    <label for="PI ">Permanent Id*:</label>
                    <h6>/* Note* In Case if AICTE permanent ID is not available please enter (AICTE Current Application ID) */</h6>
                </div>
            </div>
            <div class="col-md-4 ">
                <div>
                    <span>
                        <input type="text " id="PI " name="fname ">
                <a>Click here</a> to get permanent/current Application ID. 
                    </span>
                </div>
            </div>
            <div class="col-md-2 ">
                <div>
                    <span>
 
                    <button type="button" style="
    background: #005377;
    color: #FFFFFF;
">Check</button>
                    </span>
                </div>
            </div>
        </div>
        <br>
        <div class="row ">
            <div class="col-md-6 ">
                <div>
                    <label for="IN ">Institute Name*:</label>
                </div>
            </div>

            <div class="col-md-6 ">
                <div>
                    <span>
                        <input type="text " id="IN " name="fname ">
                    </span>
                </div>
            </div>
        </div>
        <br>
        <div class="row ">
            <div class="col-md-6 ">
                <div>
                    <span>
                        <label for="He ">Institute/University/DTE/State HE*:</label>
                    </span>
                </div>
            </div>
            <div class="col-md-6 ">
                <div>
                    <span>
                        <input type="text " id="He " name="fname ">
                    </span>
                </div>
            </div>
        </div>
        <br>

        <div class="row ">
            <div class="col-md-6 ">
                <div>
                    <span>Institute State/UT*</span>
                </div>
            </div>
            <div class="col-md-6 ">
                <div>
                    <span>
                        <input type="text " id="fname " name="fname ">
                    </span>
                </div>
            </div>
        </div>
        <br>

        <div class="row ">
            <div class="col-md-6 ">
                <div>
                    <span>
                        <label for="ID ">Institute District *:</label>
                    </span>
                </div>
            </div>
            <div class="col-md-6 ">
                <div>
                    <span>
                        <input type="text " id="ID " name="fname ">
                    </span>
                </div>
            </div>
        </div>
        <br>
        <br>



    </div>

    <div class="task_container2 ">
        <div>
            <span class="task_label " style="color: #005377; font-weight:700;padding: 10px">Details of Contact Person for any clarification regarding Syllabus / Course name :</span>

        </div>
        <hr>
        <br>
        <div class="row ">
            <div class="col-md-6 ">
                <div>
                    <label for="NP ">Name of Person*:</label>
                </div>
            </div>
            <div class="col-md-6 ">
                <div>
                    <span>
                        <input type="text " id="NP " name="fname "><br>
                        <br>
                        
                    </span>
                </div>
            </div>

            <br>
        </div>

        <div class="row ">
            <div class="col-md-6 ">
                <br>
                <div>
                    <span>
                        <label for="MN "> Mobile Number*:</label>
                    </span>
                </div>
            </div>
            <div class="col-md-6 ">
                <div>
                    <span>
                        <input type="number " id="MN " name="fname ">
                    </span>
                </div>
            </div>
            <br>
        </div>

        <div class="row ">
            <div class="col-md-6 ">
                <br>
                <div>
                    <label for="EI ">Email Id*:</label>
                </div>

            </div>
            <div class="col-md-6 ">
                <div>
                    <span>
                        <input type="email " id="EI " name="fname ">
                    </span>
                </div>
            </div>
        </div>

        <br><br>

        <div class="row ">
            <div class="col-md-6 ">

                <div>
                    <label for="Ps ">Please upload copy of syllabus*:</label>
                </div>

            </div>

            <div class="col-md-6 ">
                <div>
                    <span>
            
                    <label for="myfile" style="
    background: #005377;
    color: #FFFFFF;
"></label>
                    <input type="file" id="myfile" name="myfile" multiple=""><br><br>
                "&gt;
                </span>

                </div>
            </div>
        </div>

        <br>
        <br>

    </div>
    <div class="row">
        <div class="col-md-6"></div>
        <div class="col-md-6">
            <div>
                <div class="submit">
                    <a>
                        Submit</a>

                </div>
            </div>
        </div>
    </div>
</div>

