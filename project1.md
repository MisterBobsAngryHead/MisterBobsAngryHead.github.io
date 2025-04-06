[Back to Portfolio](./)

Windows OS CIS Compliance
===============

-   **Class: 301** 
-   **Grade: A** 
-   **Language(s): Powershell** 
-   **Source Code Repository:** [features/mastering-markdown](https://github.com/MisterBobsAngryHead/CSCI-301-code-repository/blob/master/Final)  
    (Please [email me](mailto:richardprice.cyber@gmail.com) to request access.)

## Project description

# 🔐 Windows CIS Password Policy Compliance Checker

This PowerShell script audits local Windows password and account lockout policies against the [CIS (Center for Internet Security)](https://www.cisecurity.org/) Windows security benchmarks.

---

## 📋 What It Does

The script checks the following security settings:

- ✅ **Minimum Password Length** (CIS 1.1.4)
- ✅ **Maximum Password Age** (CIS 1.1.2)
- ✅ **Minimum Password Age** (CIS 1.1.3)
- ✅ **Password Complexity Requirement** (CIS 1.1.5)
- ✅ **Account Lockout Duration** (CIS 1.2.1)

It provides color-coded feedback on whether each policy meets CIS recommendations.

---

## ⚙️ Requirements

- PowerShell (Windows PowerShell or PowerShell Core)
- Administrator privileges (required to run `secedit`)

---

## 🚀 How to Use

1. Open PowerShell **as Administrator**.
2. Save the script to your system as `Check-CIS-PasswordPolicies.ps1`.
3. Run the script

```

![screenshot](images/dummy_thumbnail.jpg)  
Fig 1. The launch screen

![screenshot](images/dummy_thumbnail.jpg)  
Fig 2. Example output after input is processed.

![screenshot](images/dummy_thumbnail.jpg)  
Fig 3. Feedback when an error occurs.

## 3. Additional Considerations

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

[Back to Portfolio](./)
