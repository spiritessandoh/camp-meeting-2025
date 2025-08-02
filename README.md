<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Youth Camp Registration</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f3f7fa;
      padding: 2rem;
      color: #333;
    }
    .form-container {
      max-width: 700px;
      margin: auto;
      background: #fff;
      padding: 2rem;
      border-radius: 12px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }
    h2, h3 {
      text-align: center;
      margin-bottom: 0.5rem;
    }
    h4 {
      margin-top: 2rem;
      color: #005b96;
      border-bottom: 1px solid #ccc;
      padding-bottom: 0.3rem;
    }
    label {
      display: block;
      margin: 1rem 0 0.3rem;
      font-weight: 500;
    }
    input[type="text"],
    input[type="email"],
    input[type="tel"],
    select,
    textarea {
      width: 100%;
      padding: 0.6rem;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 1rem;
      background: #f9f9f9;
    }
    textarea {
      resize: vertical;
      min-height: 80px;
    }
    .checkbox-group {
      display: flex;
      align-items: center;
      margin-top: 1rem;
    }
    .checkbox-group input {
      margin-right: 0.5rem;
    }
    button {
      display: block;
      width: 100%;
      margin-top: 2rem;
      padding: 0.75rem;
      background: #005b96;
      color: white;
      font-size: 1.1rem;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s ease;
    }
    button:hover {
      background: #00487c;
    }
  </style>
</head>
<body>

  <div class="form-container">
    <h2>THE CHURCH OF PENTECOST – KASOA</h2>
    <h3>CP DISTRICT YOUTH CAMP MEETING 2025</h3>
    <p style="text-align: center;">
      <strong>Theme:</strong> Unleashed to Live a Life Worthy of Your Calling<br>
      <strong>Duration:</strong> Wednesday, August 20 – Saturday, August 23 (12:00 PM)<br>
      <strong>Venue:</strong> Fredmerk School Complex
    </p>

    <form action="https://formspree.io/f/xyzpdgbn" method="POST">
      
      <h4>Personal Information</h4>
      <label>First Name* <input type="text" name="first_name" required></label>
      <label>Last Name* <input type="text" name="last_name" required></label>
      <label>Email Address <input type="email" name="email"></label>
      <label>Phone Number <input type="tel" name="phone"></label>
      <label>Age Group
        <select name="age_group" required>
          <option value="">-- Select Age Group --</option>
          <option value="Below 13">Below 13</option>
          <option value="13-19">13 – 19</option>
          <option value="20-35">20 – 35</option>
          <option value="35+">35 and above</option>
        </select>
      </label>
      <label>Local Assembly Name <input type="text" name="assembly_name"></label>

      <h4>Emergency Contact</h4>
      <label>Emergency Contact Name <input type="text" name="emergency_contact_name"></label>
      <label>Emergency Contact Phone <input type="tel" name="emergency_contact_phone"></label>

      <h4>Additional Information</h4>
      <label>Volunteer Work Preference
        <select name="volunteer_preference">
          <option value="">-- Select --</option>
          <option value="Prayer Team">Prayer Team</option>
          <option value="Media">Media</option>
          <option value="Ushering">Ushering</option>
          <option value="Cleaning">Cleaning</option>
          <option value="Commandant">Commandant</option>
        </select>
      </label>
      <label>Dietary Restrictions or Allergies
        <textarea name="dietary_restrictions" placeholder="List any restrictions or allergies..."></textarea>
      </label>
      <label>Medical Conditions or Medications
        <textarea name="medical_info" placeholder="List any important medical details..."></textarea>
      </label>

      <div class="checkbox-group">
        <input type="checkbox" name="terms" required>
        <label for="terms">I agree to the terms and conditions and understand the camp policies *</label>
      </div>

      <button type="submit">Register Now</button>
    </form>
  </div>

</body>
</html>
