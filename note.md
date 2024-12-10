<style>
    /* General Styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Georgia', serif;
      background-color: #fdf6e3; /* Warm cream */
      color: #333333; /* Charcoal */
      line-height: 1.6;
      overflow-x: hidden;
    }

    header {
      background: #013220; /* Deep green */
      padding: 20px 0;
    }

    header .container {
      display: flex;
      justify-content: center;
      align-items: center;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 30px;
    }

    nav ul li a {
      color: #d4af37; /* Gold */
      text-decoration: none;
      font-size: 18px;
      font-weight: bold;
      padding: 10px;
      transition: color 0.3s ease, border-bottom 0.3s ease;
    }

    nav ul li a:hover {
      color: #fdf6e3; /* Cream */
      border-bottom: 2px solid #d4af37; /* Gold underline */
    }

    .section {
      padding: 60px 20px;
      text-align: center;
      background: #fdf6e3; /* Soft cream background */
      margin-bottom: 40px;
    }

    .section:nth-child(odd) {
      background: #ffffff; /* Alternate light background */
    }

    .section h2 {
      color: #013220; /* Deep green */
      font-size: 32px;
      margin-bottom: 20px;
    }

    .section p {
      font-size: 18px;
      margin-bottom: 20px;
    }

    .project-list {
      display: flex;
      justify-content: center;
      gap: 30px;
      flex-wrap: wrap;
    }

    .project {
      background: #fff;
      border: 1px solid #d4af37;
      border-radius: 8px;
      padding: 20px;
      width: 300px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .project:hover {
      transform: translateY(-10px);
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
    }

    .project h3 {
      color: #013220;
      margin-bottom: 10px;
    }

    /* Contact Section */
    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      align-items: center;
    }

    input, textarea {
      padding: 15px;
      width: 90%;
      max-width: 400px;
      border: 2px solid #d4af37;
      border-radius: 8px;
      font-size: 16px;
      background: #fdf6e3;
      color: #013220;
    }

    button {
      padding: 12px 20px;
      background: #d4af37;
      color: #fff;
      font-size: 16px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    button:hover {
      background: #013220;
    }

    footer {
      background: #013220;
      color: #fdf6e3;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }

    #particles-js {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: -1;
    }
  </style>