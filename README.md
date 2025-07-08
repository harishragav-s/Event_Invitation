# Event_Invitation

### REG NO : 212222110013
### DATE : 8/7/25 

## Objective:
To design a visually appealing event invitation using HTML elements and basic CSS styling for structure and layout.

## CODE :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Event Invitation</title>
    <style>
        body {
            background-color: #fbeec1; /* light beige */
            font-family: sans-serif;
            margin: 0;
            padding: 20px;
        }

        .invite-card {
            max-width: 500px;
            background-color: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 40px auto;
            text-align: center;
        }

        .invite-card h1 {
            color: #4a4a4a;
            margin-bottom: 10px;
        }

        .invite-card h3 {
            color: #888;
            margin-bottom: 25px;
        }

        .invite-card img {
            max-width: 100%;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        .invite-card p {
            font-size: 16px;
            margin: 10px 0;
        }

        .label {
            font-weight: bold;
        }

        .rsvp {
            margin-top: 30px;
            font-size: 14px;
            padding-top: 15px;
            border-top: 1px solid #ddd;
            color: #555;
        }
    </style>
</head>
<body>

    <div class="invite-card">
        <img src="https://via.placeholder.com/500x200?text=Annual+Alumni+Meet" alt="Event Banner">
        <h1>Annual Alumni Meet</h1>
        <h3>Reconnect & Celebrate Together</h3>

        <p><span class="label">Date:</span> August 25, 2025</p>
        <p><span class="label">Time:</span> 6:00 PM onwards</p>
        <p><span class="label">Venue:</span> College Auditorium</p>

        <div class="rsvp">
            <p><strong>RSVP:</strong> John Doe — 9876543210</p>
            <p>Or email: events@college.edu</p>
        </div>
    </div>

</body>
</html>
```
