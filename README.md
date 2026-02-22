# EduDataSet
Educational datasets (all in-access)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Educational Datasets Repository</title>
    <style>
        /* General Body Styles */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f9f9f9;
        }

        /* Header Styles */
        h1 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }

        h2 {
            color: #2c3e50;
            margin-top: 30px;
        }

        /* Paragraph Styles */
        p {
            background-color: #fff;
            padding: 15px;
            border-left: 4px solid #3498db;
            margin-bottom: 20px;
        }

        /* Table Styles */
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 25px 0;
            font-size: 0.9em;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.10);
            background-color: #ffffff;
        }

        th, td {
            padding: 12px 15px;
            text-align: left;
            border: 1px solid #dddddd;
        }

        th {
            background-color: #3498db;
            color: #ffffff;
            text-transform: uppercase;
            letter-spacing: 0.03em;
        }

        tr:nth-of-type(even) {
            background-color: #f3f3f3;
        }

        tr:hover {
            background-color: #f1f1f1;
            cursor: default;
        }

        /* Link Styles */
        a {
            color: #3498db;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
        }

        /* List Styles */
        ul {
            background-color: #fff;
            padding: 20px 40px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.05);
        }

        li {
            margin-bottom: 10px;
        }

        strong {
            color: #2980b9;
        }
    </style>
</head>
<body>

    <h1>Educational Datasets Repository</h1>

    <p>
        A curated collection of widely used datasets in the fields of <strong>Educational Data Mining (EDM)</strong>, 
        <strong>Learning Analytics</strong>, and <strong>Machine Learning</strong>. This resource is designed for researchers 
        and data scientists working on student performance prediction, knowledge tracing, dropout analysis, and cognitive modeling.
    </p>

    <h2>Dataset List</h2>

    <table>
        <thead>
            <tr>
                <th>Dataset Name</th>
                <th>Brief Description</th>
                <th>Key Features (Columns/Attributes)</th>
                <th>Link / Source</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><strong>Student Performance (UCI)</strong></td>
                <td>Data from secondary school students in Portugal (Math & Portuguese language). Used to predict grades and failures.</td>
                <td>School, Sex, Age, Address, Family size, Parent's education/jobs, Study time, Failures, Health, Absences, G1, G2, G3 (Grades).</td>
                <td><a href="https://archive.ics.uci.edu/ml/datasets/Student+Performance" target="_blank">UCI ML Repository</a></td>
            </tr>
            <tr>
                <td><strong>Open University Learning Analytics (OULAD)</strong></td>
                <td>Large dataset from a UK distance learning university. Contains student demographics, interactions with VLE, and assessments.</td>
                <td>Student ID, Module, Presentation, Region, Highest Education, IMD Band, Age Band, Disability, Date of registration, Sum of clicks, Assignment scores.</td>
                <td><a href="https://analyse.kmi.open.ac.uk/open_dataset" target="_blank">Open University Website</a></td>
            </tr>
            <tr>
                <td><strong>ASSISTments</strong></td>
                <td>A massive dataset from an online math tutoring platform. Widely used for Knowledge Tracing.</td>
                <td>User ID, Problem ID, Skill ID, Correct (0/1), Attempt Number, Hint Taken, Start Time, End Time, Syllabus.</td>
                <td><a href="https://sites.google.com/site/assistmentsdata/dataset" target="_blank">ASSISTments Data Portal</a></td>
            </tr>
            <tr>
                <td><strong>PISA (OECD)</strong></td>
                <td>Global survey measuring 15-year-olds' abilities in reading, math, and science.</td>
                <td>Country, Student ID, Gender, Economic/Social/Cultural Status (ESCS), Math/Reading/Science Scores, School ID, Teacher practices.</td>
                <td><a href="https://www.oecd.org/pisa/data/" target="_blank">OECD PISA Data</a></td>
            </tr>
            <tr>
                <td><strong>Kalboard 6 (xAPI)</strong></td>
                <td>Data from an LMS used in Jordan. Designed to predict student academic performance based on behavior.</td>
                <td>Gender, Nationality, Grade, Section, Topic, Raised hands, Visited resources, Announcements viewed, Discussion groups, Student Absence Days.</td>
                <td><a href="https://www.kaggle.com/datasets/aljarah/xAPI-Edu-Data" target="_blank">Kaggle Link</a></td>
            </tr>
            <tr>
                <td><strong>EdNet</strong></td>
                <td>One of the largest public educational datasets (AIEd), collected from a Korean AI tutoring platform (TOSS).</td>
                <td>User ID, Question ID, Timestamp, User Answer, Elapsed Time, Part, Tag (Skill concept).</td>
                <td><a href="https://github.com/riiid/ednet" target="_blank">EdNet GitHub</a></td>
            </tr>
            <tr>
                <td><strong>US College Scorecard</strong></td>
                <td>Official data from the US Department of Education regarding higher education institutions.</td>
                <td>Institution Name, City/State, Average Annual Cost, SAT/ACT Scores, Retention Rate, Graduation Rate, Median Earnings, Median Debt.</td>
                <td><a href="https://collegescorecard.ed.gov/data/" target="_blank">US Dept of Education</a></td>
            </tr>
            <tr>
                <td><strong>Student Dropout and Academic Success (UCI)</strong></td>
                <td>Data from a higher education institution used to predict student dropout and academic success.</td>
                <td>Marital Status, Application mode, Course, Previous qualification, Admission grade, Curricular units (1st/2nd sem), Target (Dropout/Graduate).</td>
                <td><a href="https://archive.ics.uci.edu/ml/datasets/Student+Dropout+and+Academic+Success" target="_blank">UCI ML Repository</a></td>
            </tr>
            <tr>
                <td><strong>TIMSS</strong></td>
                <td>Trends in International Mathematics and Science Study for 4th and 8th graders.</td>
                <td>Student ID, Country, Gender, Books in home, Computer availability, Math Score, Science Score, Teacher confidence.</td>
                <td><a href="https://timssandpirls.bc.edu/" target="_blank">IEA TIMSS</a></td>
            </tr>
            <tr>
                <td><strong>MOOC User Engagement (KDD Cup 2015)</strong></td>
                <td>Data from XuetangX (Chinese MOOC platform). Used to predict dropout rates in online courses.</td>
                <td>User ID, Course ID, Enrollment ID, Start/End time, Course category, Course difficulty, Activity logs.</td>
                <td><a href="https://www.kaggle.com/c/kddcup2015-discussions" target="_blank">Kaggle KDD Cup</a></td>
            </tr>
            <tr>
                <td><strong>Algebra I (KDD Cup 2010)</strong></td>
                <td>Classic dataset used for educational data mining competitions involving algebra problem steps.</td>
                <td>Student ID, Problem Name, Step Name, Correct First Attempt, Hints, Step Duration, Error Diagnosis, Knowledge Component.</td>
                <td><a href="https://pslcdatashop.web.cmu.edu/KDDCup/" target="_blank">PSLC Datashop</a></td>
            </tr>
            <tr>
                <td><strong>Learning Analytics Kaggle Set</strong></td>
                <td>Various smaller aggregated datasets often found on Kaggle for specific projects.</td>
                <td>Hours Studied, Attendance, Sleep Hours, Previous Scores, Tutoring, Extracurricular Activities, Exam Score.</td>
                <td><a href="https://www.kaggle.com/search?q=student+performance" target="_blank">Kaggle Search</a></td>
            </tr>
        </tbody>
    </table>

    <h2>How to Choose a Dataset</h2>
    <ul>
        <li><strong>For Predicting Grades / Regression Tasks:</strong> Use <em>Student Performance (UCI)</em> or <em>Kalboard 6 (xAPI)</em>.</li>
        <li><strong>For Analyzing Online Behavior (MOOCs):</strong> Use <em>Open University Learning Analytics Dataset (OULAD)</em>, <em>EdNet</em>, or <em>MOOC User Engagement</em>.</li>
        <li><strong>For Knowledge Tracing (AI Tutors):</strong> Use <em>ASSISTments</em>, <em>EdNet</em>, or <em>Algebra I (KDD Cup 2010)</em>.</li>
        <li><strong>For Macro-Level Policy Analysis:</strong> Use <em>PISA (OECD)</em>, <em>TIMSS</em>, or <em>US College Scorecard</em>.</li>
        <li><strong>For Dropout Prediction:</strong> Use <em>Student Dropout and Academic Success (UCI)</em> or <em>OULAD</em>.</li>
    </ul>

    <footer style="margin-top: 40px; font-size: 0.8em; color: #777; text-align: center;">
        <p>Please refer to the specific license terms on the original source links provided for each dataset before usage.</p>
    </footer>

</body>
</html>
