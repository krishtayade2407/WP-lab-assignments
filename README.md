<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            width: 300px;
        }
        h2 {
            text-align: center;
        }
        label {
            font-weight: bold;
        }
        input, select, textarea {
            width: 100%;
            padding: 8px;
            margin: 5px 0 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .buttons {
            display: flex;
            justify-content: space-between;
        }
        button {
            padding: 10px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .submit-btn {
            background-color: #28a745;
            color: white;
        }
        .reset-btn {
            background-color: #dc3545;
            color: white;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Registration Form</h2>
        <form>
            <label>First Name:</label>
            <input type="text" name="first_name" required>
            
            <label>Last Name:</label>
            <input type="text" name="last_name" required>
            
            <label>Gender:</label>
            <select name="gender" required>
                <option value="">Select</option>
                <option value="Male">Male</option>
                <option value="Female">Female</option>
                <option value="Other">Other</option>
            </select>
            
            <label>Subject of Interest:</label>
            <input type="text" name="subject" required>
            
            <label>Languages Known:</label>
            <input type="text" name="languages" required>
            
            <label>Date of Birth:</label>
            <input type="text" name="dob" placeholder="dd-mm-yyyy" required>
            
            <label>Contact No.:</label>
            <input type="tel" name="contact" required>
            
            <label>Address:</label>
            <textarea name="address" rows="3" required></textarea>
            
            <label>Pin Code:</label>
            <input type="text" name="pincode" required>
            
            <label>State:</label>
            <input type="text" name="state" required>
            
            <label>Country:</label>
            <input type="text" name="country" required>
            
            <div class="buttons">
                <button type="reset" class="reset-btn">Reset</button>
                <button type="submit" class="submit-btn">Submit</button>
            </div>
        </form>
    </div>
</body>
</html>
