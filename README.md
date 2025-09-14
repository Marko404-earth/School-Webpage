<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>Sunnydale School - Welcome</title>

  <style>
    body {
      font-family: 'Helvetica', sans-serif;
      line-height: 1.6;
      margin: 20px;
    }

    h1 {
      font-size: 32px;
      font-weight: 700;
      color: #255F38;
    }

    h2.mission {
      color: #255F38;
    }
    h2#upcoming-events {
      color: #255F38;
      background-color: #AFEEEE;
    }
    h2.contact {
      color: #255F38;
    }
    .indoor {
      background-color: #E0FFFF;
      padding: 5px;
      border: 1px solid #B0E0E6;
    }
    
    .outdoor {
      background-color: #AFEEEE;
      padding: 5px;
      border: 1px solid #B0E0E6;
    }

    .section {
      background-color: #4E9F3D;
      padding: 10px;
    }
  </style>
</head>
<body>

  <h1>Sunnydale School</h1>

  <h2 class="mission">Mission Statement</h2>
  <p>At Sunnydale School, we strive to provide a nurturing environment that fosters academic excellence, creativity, and growth in all our students.</p>

  <h2 id="upcoming-events">Upcoming Events</h2>
  <ul>
    <li title="Event Type: outdoor" data-event-type="indoor" class="indoor">Science Fair - <span style="font-weight: bold; color: red;">June 10</span></li>
    <li title="Event Type: Outdoor" data-event-type="outdoor" class="outdoor">Art Exhibition - <span style="font-weight: bold; color: red;">June 15</span></li>
    <li title="Event Type: Outdoor" data-event-type="outdoor" class="outdoor">Sports Day - <span style="font-weight: bold; color: red;">June 20</span></li>
  </ul>

  <h2 class="contact">Contact Us</h2>
  <div class="section">
    <p>Email: <a href="mailto:info@sunnydaleschool.edu" title="Click to copy email">info@sunnydaleschool.edu</a></p>
    <p>Phone: <a href="tel:+1234567890" title="Click to copy phone number">+1 (234) 567-890</a></p>
  </div>

</body>
</html>
