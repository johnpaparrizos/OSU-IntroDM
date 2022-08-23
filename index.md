---
layout: default
---



<link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.10.21/css/jquery.dataTables.min.css" />
<script src="https://code.jquery.com/jquery-3.5.1.js"></script>
<script src="https://cdn.datatables.net/1.10.21/js/jquery.dataTables.min.js"></script>  


# FALL 2022

## Class Information

Item                     | Section 7824                 
------------------------ | -----------                  
Schedule                 | Wed/Fri 11:10 AM - 12:25 PM   
 Location                | Scott Lab E125
 Professor               | Thomas Bihari (bihari.5@osu.edu) for first few weeks, then John Paparrizos (paparrizos.1@osu.edu)
 Professor Office Hours  | TBD
 TA                      | TBD
 TA Office Hours         | TBD                         



## Description: 
This class aims to introduce the knowledge discovery process, key data mining techniques, efficient high performance mining algorithms and provide a broad based exposure to the applications of data mining. This webpage will serve as the source of information for the course. We will post all python/R, jupyter notebooks, pdfs, lecture notes and other information on Carmen portal.

## Grading Plan: 
1. Homework x5: 60%
2. Participation/Attendance: 5%
3. Midterm Exam: 15%
4. Final Exam: 20%
5. No course project
6. Bonus points up to 5%

## Textbooks:
No one textbook, please feel free to refer to the below


1. [(Primary) Data Mining: Concepts and Techniques, 3rd edition, Morgan Kaufmann, Jiawei Han, Micheline Kamber, and Jian Pei.](http://hanj.cs.illinois.edu/bk3/)
2. [(Primary) Introduction to Data Mining, Pang-Ning Tan, Michael Steinbach, and Vipin Kumar](http://www-users.cs.umn.edu/~kumar/dmbook/index.php)
3. [(Supplementary) Data Mining Analysis and Concepts (Online version available), Mohammed J. Zaki and Wagner Meira, Jr.](http://www.dataminingbook.info/pmwiki.php/Main/BookDownload)
4. [(Supplementary) Mining of Massive Datasets (Online version available), Jure Leskovec, Anand Rajaraman and Jeffrey Ullman](http://www.mmds.org/)
5. [(Supplementary) Machine Learning, Tom Mitchell](http://www.cs.cmu.edu/~tom/mlbook.html)
6. [(Supplementary) Pattern Recognition and Machine Learning, Christopher M. Bishop](http://research.microsoft.com/en-us/um/people/cmbishop/prml/)

## Class course

<table class="display" border=1 frame=sides rules=all>
  {% for row in site.data.Syllabus %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th>{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}

    {% tablerow pair in row %}
      {{ 	pair[1] }}
    {% endtablerow %}
  {% endfor %}
</table>
