# Google Summer Of Code 2020 (GSoC)

The student will be more likely selected if he/she:

1. Contribute to Casbin related project before.
2. Familiar with the techniques required by the idea he selected.
3. Show the previous code related to the idea on personal website or GitHub.
4. Provide a personal website and descriptions for previous work/projects.
5. Provide demo sites for the previous projects if possible.
6. Provide a resume/CV.

## Idea list

### 1. Casbin Dashboard

#### Description

Build a web UI dashboard/admin portal for Casbin & Casbin-Server. It can:

1. Manage models, adapters, enforcers. The adapter manager should handle different DBs.
2. Model editor with a syntax and semantic validator.
3. Policy editor, it should be able to handle 10,000+ more rules.
4. A test page to make example request to Casbin and get response, like Postman. So users can test their model and policy.
5. Authentication and authorization for the dashboard itself. Of course authorization will be implemented in Casbin (we proudly dogfood our own product :))

The current progress is: https://dashboard.casbin.org/. Source code: https://github.com/casbin/casbin-dashboard. We want the student to continue the work.

#### Requirements

1. Golang (backend)
2. Javascript + React + Ant Design (frontend)
3. Casbin

#### Mentor

[Yang Luo](https://github.com/hsluoyz), Casbin founder


### 2. Casbin for Node.js

#### Ideas 

1. Adapters(https://casbin.org/docs/en/adapters)

**Idea**

- Implement PostgreSQL adapter
- Implement MySQL adapter   
- Implement SQL Server adapter

**Difficulty** 

Easy

2. RBAC links

**Idea**

We plan to build RBAC incrementally when the policy changes.

**Difficulty** 

Medium-Hard

#### Requirements

1. Node.js
2. TypeScript

#### Mentor

[Zixuan Liu](https://github.com/nodece), Casbin member
