# Oracle Fusion Sandbox Customization & Personalization Project

## 📌 Project Overview
This project demonstrates extensive hands-on implementation of Oracle Fusion HCM Sandbox Customizations and UI Personalization. The project focuses on modifying and enhancing the Oracle Fusion user experience using Sandbox environments, Page Composer, Appearance settings, Structure customization, User Interface Text, HCM Design Studio, and Expression Language (EL).

The implementation includes multiple real-time customization scenarios with screenshots and configuration examples showcasing how Oracle Fusion applications can be personalized according to business requirements without impacting the base application.

---

# 🎯 Objectives

- Configure and manage Oracle Fusion Sandboxes
- Perform UI Personalization using Page Composer
- Customize Navigator and Springboard
- Modify Appearance and Themes
- Customize Structure and Page Layouts
- Configure User Interface Text
- Implement HCM Design Studio configurations
- Apply Expression Language (EL) conditions
- Customize labels, tabs, fields, menus, and layouts
- Perform conditional rendering and visibility logic
- Demonstrate migration and rollback activities
- Capture screenshots for all implementations

---

# 🛠️ Technologies & Tools Used

- Oracle Fusion HCM
- Oracle Sandbox
- Page Composer
- HCM Design Studio
- Expression Language (EL)
- Oracle ADF Framework
- Oracle WebCenter Page Composer
- User Interface Text Tool
- Structure Tool
- Appearance Configuration
- Navigator & Springboard Customization

---

# 📂 Project Modules Covered

## 1️⃣ Sandbox Management

Implemented complete Sandbox lifecycle management including:

- Sandbox Creation
- Sandbox Activation
- Sandbox Publishing
- Sandbox Deletion
- Sandbox Testing
- Multiple User Sandbox Handling
- Customization Isolation

### Key Concepts
- Working with Sandboxes
- Types of Sandboxes
- Customization Layers
- Site Level Customizations
- User Level Personalizations
- Organization-Level Configurations

---

# 2️⃣ Page Composer Customization

Implemented runtime UI customizations using Page Composer.

## Activities Performed

### ✔ Customizing Page Components
- Modified fields and regions
- Updated labels
- Hidden unwanted components
- Added custom components

### ✔ Shared Component Customization
- Reused components across pages
- Managed shared customization behavior

### ✔ Adding Content
- Added static and dynamic content
- Added hyperlinks
- Added custom HTML regions

### ✔ Page Appearance Changes
- Changed page titles
- Customized layouts
- Modified icons and UI sections

### ✔ Smart Navigation Customization
- Hidden assignment names
- Modified menu options
- Customized navigation entries

### ✔ Folder & Tab Management
- Renamed tabs
- Reordered tabs
- Added new tabs

### ✔ Field Management
- Reordered fields
- Hidden popup messages
- Changed labels dynamically

---

# 3️⃣ Appearance Customization

Configured Fusion UI appearance settings including:

- Theme Customization
- Layout Configuration
- Social Layout Setup
- Announcement Layout
- None Layout Configuration

## Appearance Features Worked On

- Theme Management
- UI Branding
- Navigation Styling
- User Experience Improvements
- Responsive UI Adjustments

---

# 4️⃣ Structure Tool Customization

Performed structure-based customizations for Fusion navigation and page hierarchy.

## Implementations

- Navigator Customization
- Springboard Customization
- Menu Structure Changes
- Category Reordering
- Custom Link Configuration
- Functional Area Visibility

---

# 5️⃣ User Interface Text Customization

Customized standard Oracle Fusion UI labels and text.

## Changes Performed

- Renamed standard labels
- Modified page headings
- Updated field labels
- Customized section names
- Changed button text
- Modified instructional text

---

# 6️⃣ HCM Design Studio Configuration

Implemented HCM Design Studio configurations for transaction-level personalization.

## Activities Covered

- Rule-Based UI Configuration
- Context-Sensitive Field Behavior
- Region Visibility Control
- Business Rule Driven Personalization
- Dynamic UI Rendering
- Page Simplification

---

# 7️⃣ Expression Language (EL) Implementation

Implemented multiple Expression Language use cases for dynamic runtime personalization.

---

# 🔥 EL Use Cases Implemented

## ✔ Conditional Visibility

```EL
#{pageFlowScope.pRoleTypeCode == 'WORKER'}
```

Used for:
- Showing/Hiding regions
- Role-based visibility
- Conditional component rendering

---

## ✔ Dynamic Label Changes

```EL
#{pageFlowScope.pHeaderText} of #{bindings.DisplayName.inputValue}
```

Used for:
- Dynamic page headers
- Personalized labels
- Context-sensitive UI text

---

## ✔ Mandatory Field Logic

```EL
#{bindings.Country1.inputValue=="United States"}
```

Used for:
- Dynamic mandatory fields
- Country-based validations
- Conditional field requirements

---

## ✔ Conditional Formatting

```EL
#{row.UserStatus=='Active - Payroll Eligible' ? 'color:#0000FF' : 'color:#000000'}
```

Used for:
- Dynamic styling
- Conditional font colors
- Status-based highlighting

---

## ✔ Security-Based Visibility

```EL
#{securityContext.userName=='HCM_IMPL'}
```

Used for:
- User-specific navigation
- Security-driven access
- Personalized links

---

## ✔ Table Component Logic

```EL
#{row.TasksLeft>0 ? true : false}
```

Used for:
- Dynamic table behavior
- Row-level personalization
- Runtime validations

---

# 📸 Screenshots Included

This repository contains screenshots for:

- Sandbox Creation & Activation
- Page Composer Customizations
- Appearance Changes
- Navigator Customization
- Springboard Configuration
- User Interface Text Updates
- HCM Design Studio Rules
- EL Runtime Conditions
- Label Modifications
- Page Layout Changes
- Tab Reordering
- Dynamic Visibility Logic
- Hyperlink Configuration
- Theme Changes
- Migration Activities

---

# 🔄 Migration & Rollback Activities

Implemented:

- Page Composer Migration
- Upload & Download Customizations
- Rollback Activities
- Sandbox Publishing
- Testing Before Deployment

---

# 📚 Key Learning Outcomes

Through this project, the following concepts were learned and implemented:

- Oracle Fusion Runtime Customization
- Sandbox Isolation Strategy
- UI Personalization Best Practices
- Dynamic Expression Language Logic
- Page Composer Architecture
- HCM Design Studio Rules
- Navigation Personalization
- Appearance Configuration
- Structure Tool Usage
- Runtime vs Design-Time Customizations
- Conditional Rendering in Fusion Applications

---

# 🧠 Business Benefits

- Improved user experience
- Reduced navigation complexity
- Simplified user interface
- Role-based personalization
- Better accessibility
- Enhanced productivity
- Reduced training effort
- Business-specific UI behavior
- Flexible runtime customizations

---



---

# 🚀 Future Enhancements

- Advanced EL logic implementation
- Groovy scripting integration
- Redwood UI customization
- Role-based dashboard personalization
- Dynamic workflow personalization
- Responsive layout enhancements
- Integration with Visual Builder Studio

---

# 📖 References

- Oracle Fusion HCM Documentation
- Oracle Page Composer Documentation
- Oracle ADF Expression Language Guide
- Oracle HCM Design Studio Documentation
- Oracle Sandbox Configuration Guide

---

# 👨‍💻 Author

Developed as part of Oracle Fusion HCM technical learning and hands-on implementation project focused on Sandbox Customization, Personalization, and UI Enhancements.

---

# ⭐ Conclusion

This project demonstrates practical implementation experience in Oracle Fusion HCM Sandbox Customization and UI Personalization. It showcases the ability to perform enterprise-level runtime customizations using Oracle-recommended tools and frameworks while maintaining upgrade-safe configurations.
