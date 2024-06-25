# Finlay Cameron
**Email:** finjimcam11@gmail.com
**GitHub:** [Your GitHub](https://github.com/finjimcam)  

---

## Profile
Aspiring data analyst with a passion for football and a strong foundation in coding and data analysis. Currently a student with hands-on experience in various coding projects and football-related work. Seeking an opportunity to gain work experience in football data analysis in the UK.

---

## Education
**Univeristy of Glasgow**  
*Degree:* BSc in Computer Science (Expected Graduation: 2026)  
*Relevant Elective Studies:* Statistics
---

## Coding Projects
### Project Title 1
**Description:** Brief description of the project, what technologies were used, and your role.  
**Technologies:** Python, Pandas, NumPy, Matplotlib  
**GitHub:** [Link to Project](https://github.com/yourprofile/project1)

### Project Title 2
**Description:** Brief description of the project, what technologies were used, and your role.  
**Technologies:** R, ggplot2, Shiny  
**GitHub:** [Link to Project](https://github.com/yourprofile/project2)

### Project Title 3
**Description:** Brief description of the project, what technologies were used, and your role.  
**Technologies:** SQL, Tableau, Excel  
**GitHub:** [Link to Project](https://github.com/yourprofile/project3)

---

## Work Experience

**Filter by Category:**
<select id="categoryFilter" onchange="filterExperience()">
  <option value="all">All</option>
  <option value="football">Football</option>
  <option value="coding">Coding/Data Analysis</option>
</select>

<div id="workExperience">
  <div class="experience football">
    ### Role Title - Organisation Name
    **Location:** City, Country  
    **Dates:** Month Year - Month Year  
    **Description:** Brief description of your responsibilities and achievements in this role.
  </div>

  <div class="experience football">
    ### Role Title - Organisation Name
    **Location:** City, Country  
    **Dates:** Month Year - Month Year  
    **Description:** Brief description of your responsibilities and achievements in this role.
  </div>

  <div class="experience coding">
    ### Role Title - Organisation Name
    **Location:** City, Country  
    **Dates:** Month Year - Month Year  
    **Description:** Brief description of your responsibilities and achievements in this role.
  </div>

  <div class="experience coding">
    ### Role Title - Organisation Name
    **Location:** City, Country  
    **Dates:** Month Year - Month Year  
    **Description:** Brief description of your responsibilities and achievements in this role.
  </div>
</div>

<script>
function filterExperience() {
  var filter = document.getElementById("categoryFilter").value;
  var experiences = document.getElementsByClassName("experience");

  for (var i = 0; i < experiences.length; i++) {
    if (filter === "all") {
      experiences[i].style.display = "block";
    } else {
      if (experiences[i].classList.contains(filter)) {
        experiences[i].style.display = "block";
      } else {
        experiences[i].style.display = "none";
      }
    }
  }
}
</script>

---

## Skills
- **Programming Languages:** Python, R, SQL, JavaScript
- **Data Analysis Tools:** Pandas, NumPy, Matplotlib, ggplot2, Tableau, Excel
- **Web Development:** HTML, CSS, JavaScript, Flask
- **Other Skills:** Data Cleaning, Statistical Analysis, Machine Learning, Data Visualization

---

## Certifications
- **Certification Name** - Issuing Organisation (Month Year)  
  Brief description or relevance of the certification.

---

## Extracurricular Activities
### Football Team Name
**Role:** Player/Coach/Manager  
**Description:** Brief description of your role and achievements in the team.

### Tech Club/Organization
**Role:** Member/Leader  
**Description:** Brief description of your role and contributions.

---

## References
Available upon request.
