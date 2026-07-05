---
layout: home
title: Daniel Foo   IT Procurement & Cloud Cost Optimization Specialist
description: IT Procurement Manager with 20+ years in cloud cost optimization. Saved $3.9M+ in AWS TCO, AWS/GCP certified, and FinOps specialist.
---

# **Daniel Foo**

**IT Procurement Manager | Cloud Cost Specialist | FinOps Practitioner**

---
### 🎯 **Value Proposition**
I help enterprises **cut cloud costs by 20-40%** through **FinOps, strategic procurement, and data-driven optimization**. With **20+ years** across Marine, Oil & Gas, Telco, and IT sectors, I combine **deep procurement expertise** with **AWS/GCP certifications** and **Python/SQL skills** to drive financial efficiency at scale.

[View My Work](#-portfolio) • [Get in Touch](#-contact)

---

## 🏆 **Key Achievements**
<div class="achievements-grid">
  <div class="achievement-card">
    <h3>$3.9M</h3>
    <p><strong>AWS TCO Reduction</strong><br>
    Negotiated 3-year AWS Enterprise Agreement for Singtel, optimizing service commitments and consolidating spend.</p>
  </div>
  <div class="achievement-card">
    <h3>40%</h3>
    <p><strong>Cost Savings</strong><br>
    Led Dynatrace → Elastic migration, cutting monitoring costs by 40% ($375K/3yr).</p>
  </div>
  <div class="achievement-card">
    <h3>$5M+</h3>
    <p><strong>Annual Spend Managed</strong><br>
    Oversaw IT procurement across 50+ vendors at Singtel.</p>
  </div>
  <div class="achievement-card">
    <h3>8-12%</h3>
    <p><strong>Cost Reduction</strong><br>
    Achieved through benchmark studies and strategic sourcing.</p>
  </div>
</div>

---
## 💼 **Portfolio**

### **Cloud Cost Optimization**
 | Project | Technology | Impact | Link |
 |---------|------------|--------|------|
 | **AWS/GCP Cost Dashboard** | Python, BigQuery, AWS Cost Explorer | Identified **$500K+/year savings** | [Case Study](#) |
 | **AWS Enterprise Agreement** | AWS, FinOps | **$3.9M TCO reduction** | [Details](#) |
 | **Automated Spend Reports** | Python, PostgreSQL | Reduced report time by **80%** | [GitHub](#) |

### **Vendor & Procurement**
 | Project | Scope | Impact |
 |---------|-------|--------|
 | **Dynatrace → Elastic Migration** | Enterprise monitoring | **40% cost reduction** ($125K/year) |
 | **Global Vendor Consolidation** | 50+ vendors | **8-12% cost savings** |
 | **SAP Ariba Implementation** | Procurement system | **96% on-time delivery** |

---
## 🛠 **Skills**

### **Technical Skills**
{% for skill in site.skills.technical %}
- **{{ skill.name }}** <span class="skill-level">{{ skill.level }}%</span>
  <div class="skill-bar" style="width: {{ skill.level }}%;"></div>
{% endfor %}

### **Professional Skills**
{% for skill in site.skills.professional %}
- **{{ skill.name }}** <span class="skill-level">{{ skill.level }}%</span>
  <div class="skill-bar" style="width: {{ skill.level }}%;"></div>
{% endfor %}

---
## 🎓 **Education & Certifications**
 | Year | Qualification | Institution |
 |------|---------------|-------------|
 | 2024 | Certified Scrum Product Owner | Scrum Alliance |
 | 2023 | AWS Certified Cloud Practitioner | Amazon Web Services |
 | 2022 | GCP Associate Cloud Engineer | Google Cloud |
 | 2021 | GCP Professional Cloud Architect | Google Cloud |
 | 2009 | MSc in Maritime Studies | NTU Singapore |
 | 2006 | BSc in Transport & Logistics Mgmt (Distinction) | RMIT University |

---
## 🏆 **Awards**
- **Google Cloud Star Learner** – TCS Singapore (2023)
- **MSc. Scholarship** – Tanker Pacific Management (2007)

---
## 🌍 **Languages**
- **Chinese** (Native)
- **English** (Professional)
- **Malay** (Professional)
- **French** (Conversational)

---
## 📞 **Contact**
**Let’s discuss how I can help your team cut cloud costs by 20-40%.**

<div class="contact-buttons">
  <a href="mailto:danielfootc@gmail.com" class="btn btn-primary">
    <i class="fas fa-envelope"></i> Email Me
  </a>
  <a href="https://linkedin.com/in/danielfootc" class="btn btn-linkedin">
    <i class="fab fa-linkedin"></i> Connect on LinkedIn
  </a>
  <a href="https://github.com/danielfootc" class="btn btn-dark">
    <i class="fab fa-github"></i> View GitHub
  </a>
  <a href="/assets/files/Daniel_Foo_Resume.pdf" download class="btn btn-outline">
    <i class="fas fa-download"></i> Download Resume
  </a>
</div>

---
<style>
  /* Achievement Cards */
  .achievements-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1.5rem;
    margin: 2rem 0;
  }
  .achievement-card {
    background: #f8f9fa;
    border: 1px solid #dee2e6;
    border-radius: 8px;
    padding: 1.5rem;
    text-align: center;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  }
  .achievement-card h3 {
    color: #0d6efd;
    font-size: 2.5rem;
    margin: 0 0 0.5rem;
  }
  .achievement-card p {
    margin: 0;
    font-size: 0.9rem;
    color: #495057;
  }
  
  /* Skill Bars */
  .skill-level {
    font-size: 0.8rem;
    color: #6c757d;
    float: right;
  }
  .skill-bar {
    height: 8px;
    background: #0d6efd;
    border-radius: 4px;
    margin-top: 4px;
    transition: width 0.5s ease;
  }
  
  /* Contact Buttons */
  .contact-buttons {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    justify-content: center;
    margin: 2rem 0;
  }
  .btn {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    padding: 0.75rem 1.5rem;
    border-radius: 4px;
    text-decoration: none;
    font-weight: 500;
    transition: all 0.2s ease;
  }
  .btn-primary {
    background: #0d6efd;
    color: white;
  }
  .btn-primary:hover {
    background: #0b5ed7;
  }
  .btn-linkedin {
    background: #0077b5;
    color: white;
  }
  .btn-linkedin:hover {
    background: #005682;
  }
  .btn-dark {
    background: #212529;
    color: white;
  }
  .btn-dark:hover {
    background: #343a40;
  }
  .btn-outline {
    background: transparent;
    border: 1px solid #6c757d;
    color: #495057;
  }
  .btn-outline:hover {
    background: #f8f9fa;
  }
  
  /* Responsive */
  @media (max-width: 768px) {
    .achievements-grid {
      grid-template-columns: repeat(2, 1fr);
    }
    .contact-buttons {
      flex-direction: column;
      align-items: center;
    }
    .btn {
      width: 100%;
      justify-content: center;
    }
  }
</style>
