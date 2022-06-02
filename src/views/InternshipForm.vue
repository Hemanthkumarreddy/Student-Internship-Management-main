<template>
    <div class="internshipForm">
        <form name="StuForm">
            <div class="container">
                <h1> Student Registeration Form</h1>
                <hr>
                <label> Firstname: </label>
                <input type="text" name="firstname" placeholder="Firstname" size="15">
                <label> Lastname: </label>
                <input type="text" name="lastname" placeholder="Lastname" size="15">
                <div>
                    <label>
                        Major :
                    </label>

                    <select>
                        <option value="Comp">Computers</option>
                        <option value="EEE">ELECTRICAL</option>
                        <option value="Bus">Business</option>
                        <option value="PhyEd">Physical Education</option>
                    </select>

                    <div>
                    </div>
                    <label>
                        Student Status :
                    </label><br>
                    <div>
                        <input type="radio" id="UnderGrad" name="stuStatus" value="UnderGrad" unchecked>
                        <label for="UnderGrad">UnderGraduate Student</label>
                    </div>

                    <div>
                        <input type="radio" id="Grad" name="stuStatus" value="Grad" unchecked>
                        <label for="Grad">Graduate Student</label>
                    </div>
                    <div>
                    </div>
                    <label>
                        Gender :
                    </label><br>
                    <input type="radio" value="Male" name="gender" checked> Male
                    <input type="radio" value="Female" name="gender"> Female
                    <input type="radio" value="Other" name="gender"> Other

                </div>
                <label>
                    Phone :
                </label>
                <input type="text" name="country code" placeholder="Country Code" value="+1" size="2">
                <input type="text" name="phone" placeholder="phone no." size="10" required>
                Current Address :
                <textarea cols="80" rows="5" placeholder="Current Address" value="address" required></textarea>
                <label for="Employer"><b>Company Name:</b></label>
                <input type="text" placeholder="Enter Employer Name" name="Employer" required>

                <label for="pos"><b>Position:</b></label>
                <input type="text" placeholder="Enter Desingnation" name="pos" required>

                <label for="job"><b>Job ID:</b></label>
                <input type="text" placeholder="Job ID" name="job" required>

                <label for="loc"><b>Location:</b></label>
                <input type="text" placeholder="Location of Internship" name="loc" required>


                <p>
                    <input type="submit" value="Submit" name="Submit">
                    <input type="reset" value="Reset" name="Reset">
                </p>
            </div>
        </form>
    </div>

</template>

<style>
body {
    font-family: Calibri, Helvetica, sans-serif;
}

.container {
    padding: 50px;
    background-color: rgb(224, 230, 173);
}

input[type=text],
input[type=password],
textarea {
    width: 100%;
    padding: 15px;
    margin: 5px 0 22px 0;
    display: inline-block;
    border: none;
    background: #f1f1f1;
}

input[type=text]:focus,
input[type=password]:focus {
    background-color: orange;
    outline: none;
}

div {
    padding: 10px 0;
}

hr {
    border: 1px solid #f1f1f1;
    margin-bottom: 25px;
}

.registerbtn {
    background-color: #4CAF50;
    color: white;
    padding: 16px 20px;
    margin: 8px 0;
    border: none;
    cursor: pointer;
    width: 100%;
    opacity: 0.9;
}

.registerbtn:hover {
    opacity: 1;
}
</style>