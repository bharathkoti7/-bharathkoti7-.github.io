<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="form1.css">
</head>
<body>
    <div id="content">
        <form id="form">
            <h1 id="heading">Application For Permission To Date My Daughter</h1>
            <p id="Note"> <b>Note:</b> Form is to be completed at least 21 days prior to date</p>

            <fieldset class="fields">
                <legend>Personal Details</legend>
                    <div class="Details">
                        <label>Name:</label>
                        <input type="text" placeholder="Enter your name" required>
                    </div>

                    <div class="Details">
                        <label>Address:</label>
                        <input type="text" placeholder="Enter Address" required>
                    </div>

                    <div class="Details">
                        <label>Email:</label>
                        <input type="text" placeholder="Enter your mail" required>
                    </div>

                    <div class="Details">
                        <label>Phone Number:</label>
                        <input type="text" placeholder="Enter 10 digit Number" required>
                    </div>

                    <div class="Details">
                        <label>IQ:</label>
                        <input type="text" placeholder="EnterIQ " required>
                    </div>

                    <div class="Details gender" >
                        <label>Gender:</label>
                        <input type="radio" name="gender" value="Male">
                        <label>Male</label>
                        <input type="radio" name="gender" value="Female">
                        <label>Female</label>
                        <input type="radio" name="gender" value="Others">
                        <label>Others</label>
                    </div>
                    <div class="Details">
                        <label>Date of Proposed Outing:</label>
                        <input type="date">
                    </div>
            </fieldset>

            <fieldset class="fields">
                <div>
                    Check All That Apply
                </div>
                <div class="Details">
                    <div>
                        <input type="checkbox" name="choose">
                        <label>I have tattoos and/or piercings</label>
                    </div>
                    
                    <div>
                        <input type="checkbox" name="choose">
                        <label>I am more than 2 years older than my daughter</label>
                    </div>

                    <div>
                        <input type="checkbox" name="choose">
                        <label>I own a panel van or V8 ute</label>
                    </div>

                    <div>
                        <input type="checkbox" name="choose">
                        <label>I work full-time</label>
                    </div>

                    <div>
                        <input type="checkbox" name="choose">
                        <label>My parents are rich</label>
                    </div>

                    <div>
                        <input type="checkbox" name="choose">
                        <label>Is the date at a well lit public location</label>
                    </div>
                </div>
            </fieldset>
            
            <fieldset class="fields">
                <div>
                    <label>Political Persuasion:</label>
                    <input list="p-view" value="left Wing">
                    <datalist id="p-view">
                        <option>Left Wing</option>
                        <option>Right Wing</option>
                        <option>Conservative</option>
                        <option>Nazi</option>
                    </datalist>

                    <label>Education Level Completed</label>
                    <input list="education" value="University">
                    <datalist id="education">
                        <option>University</option>
                        <option>College</option>
                        <option>High school</option>
                        <option>None</option>
                    </datalist>
                </div>
            </fieldset>

            <fieldset class="fields">
                <legend>Essay Section</legend>
                <p>In 50 words or more explain why you want to date my daughter</p>
                <textarea placeholder="Enter text here" rows="5" cols="20"></textarea>
                <p>Please upload contact details for 2 references</p>
                <textarea placeholder="Enter text here" rows="5" cols="20"></textarea>
                <p>Upload Police Clearance Certificate, Bank Statement and Medical Certifiates here:</p>
                <button>Attach files</button>
            </fieldset>

            <div id="buttons">
                <button >Send your Application</button>
            </div>
        </form>
    </div>
</body>
</html>