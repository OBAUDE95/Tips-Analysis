<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Titanic Survival Analysis.</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 2rem;
      background-color: #f9f9f9;
      color: #333;
    }
    h1, h2, h3 {
      color: #003366;
    }
    ul {
      margin-left: 1.5rem;
    }
    code {
      background: #eee;
      padding: 2px 6px;
      border-radius: 4px;
    }
    .section {
      margin-bottom: 2rem;
    }
    img {
      max-width: 100%;
      border: 1px solid #ccc;
      border-radius: 6px;
      margin-top: 1rem;
    }
  </style>
</head>
<body>

  <h1>🚢 Titanic Survival Analysis</h1>

  <div class="section">
    <h2>🌊 Project Overview</h2>
    <p>
      This project explores passenger data from the Titanic disaster to analyze survival patterns.
      By leveraging data visualization and statistical analysis, we uncover how factors such as class,
      gender, and age influenced survival rates during the tragic event.
    </p>
  </div>

  <div class="section">
    <h2>🎯 Project Objective</h2>
    <ul>
      <li>Analyze survival rates based on demographic and ticket attributes.</li>
      <li>Identify the most influential factors in determining survival.</li>
      <li>Communicate findings with clear visuals using Power BI.</li>
    </ul>
  </div>

  <div class="section">
    <h2>🧠 Methodology</h2>
    <ul>
      <li><strong>Data Cleaning:</strong> Removed null values, encoded categorical variables.</li>
      <li><strong>Segmentation:</strong> Grouped data by class, sex, age brackets, and fare ranges.</li>
      <li><strong>Visualization:</strong> Created charts to represent survival proportions and class comparisons in Power BI.</li>
    </ul>
    <p><strong>Tools Used:</strong> Power BI, Excel, DAX</p>
  </div>

  <div class="section">
    <h2>📊 Key Insights</h2>
    <ul>
      <li><strong>Gender Matters:</strong> Women had a significantly higher survival rate than men.</li>
      <li><strong>Class Disparity:</strong> Passengers in First Class were more likely to survive compared to those in Third Class.</li>
      <li><strong>Age Range:</strong> Children and younger passengers had slightly better survival rates than older adults.</li>
      <li><strong>Fare:</strong> Higher ticket fares loosely correlated with higher survival rates, hinting at privilege in evacuation access.</li>
    </ul>

    <h3>📷 Survival Distribution Histogram</h3>
    <p>This histogram illustrates the overall distribution of passengers who survived versus those who didn't:</p>
    <img src="histogram.JPG" alt="Survival Histogram showing survival distribution">
  </div>

  <div class="section">
    <h2>✅ Conclusion</h2>
    <p>
      The Titanic dataset highlights how socio-economic status and gender influenced chances of survival.
      This project demonstrates how data can bring historical events to life and inform ethical discussions around
      equality, access, and crisis response.
    </p>
  </div>

  <div class="section">
    <h2>🚀 Future Enhancements</h2>
    <ul>
      <li>Introduce a predictive model using logistic regression or decision trees.</li>
      <li>Deploy a dashboard using Streamlit for interactive exploration.</li>
      <li>Compare Titanic data with modern transportation safety data for longitudinal insights.</li>
    </ul>
  </div>

  <div class="section">
    <h2>📁 Project Files</h2>
    <pre>
📦 Titanic_Survival_Analysis
├── titanic_survival_dashboard.pbix
├── dataset/
│   └── titanic_cleaned.csv
├── visuals/
│   └── survival_by_class.png
│   └── histogram.JPG
└── README.html
    </pre>
  </div>

  <div class="section">
    <h2>👤 Author</h2>
    <p><strong>Opeyemi Morakinyo</strong></p>
    <p>Email: <a href="mailto:opeyemi.morakinyo@email.com">opeyemi.morakinyo@email.com</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/opeyemi-morakinyo" target="_blank">linkedin.com/in/opeyemi-morakinyo</a></p>
    <p>GitHub: <a href="https://github.com/opeyemianalyst" target="_blank">github.com/opeyemianalyst</a></p>
  </div>

</body>
</html>
