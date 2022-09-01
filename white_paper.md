# Poluchka
*September 1, 2022*

#### Abstract

The purpose of this text is to provide the first description of the Poluchka (Paycheck). In order to reduce the size of the document to reasonable limits, we will focus mainly on the unique features of the service that are important in order to achieve the stated goals.

## Introduction

Poluchka (Paycheck) is a fast, secure and simple solution for managing employee attendance and payroll, as well as being user-friendly. We strive to ensure that every small and medium-sized business owner can know exactly where their employees are, whether the work has been done, and when payroll will occur.

This text is not intended to be a definitive reference for all implementation details. Some details may be subject to change during development and testing.

## Contents

[1 Brief description of the main functions](#1-brief-description-of-the-main-functions) 

[2 General information](#2-general-information)

[3 Expanding capabilities](#3-expanding-capabilities) 

## 1 Brief description of the main functions

Poluchka (Paycheck) is a combination of the following components:

- A simple and convenient platform that allows you to track employee attendance automatically or manually in a single click. Geo-positioning from your cell phone is used for tracking. Check staff presence in the office or a designated location. Employees can mark their own attendance with a photo report.
- Poluchka will automatically calculate employee wages based on attendance data and based on wages including overtime, penalties for lateness, bonuses, vacation and part-time work.
- Tracking of working hours, when a person came to work, and recording of leaving the workplace. The employee is given access to information about their attendance and salary schedule.
- Set up automatic scheduled payroll payments without commissions or interest. Avoid the hassle of calculating expenses at the end of the month, because you can ensure that all your employees are paid continuously on a flexible schedule: monthly, hourly and piece-rate pay.
- Notify staff about payments, bonuses, attendance, and vacations through various communication channels such as texting, Telegram/WhatsApp, or email.
- Track employee performance and attendance with easy-to-understand reports. Poluchka allows you to generate a payroll report and attendance register in PDF format and share it with employees.
- 
As long as these functions are seen as the main ones and are the core of the Poluchka project, the other components can be seen as auxiliary, and they are useful and interesting in their own right. Taken together, the auxiliary components allow the service to be more versatile than would be possible with just the core features.

## 2 General information

We begin with a description of Poluchka, the main component of the project. Our approach here is top-down: first we give a general description of the entire project, and then we describe each of its components in more detail.

#### 2.1 Problem description

Description Historically, there has been an undeniable gap in business services in Russia. There were nearly 6 million small and medium-sized enterprises (SMEs) in the country, employing 15 million people. But unlike their larger counterparts, service providers ignored SMEs, who felt that the cost of developing and maintaining them was too high to justify the effort. As a result, SMEs were forced to combine spreadsheets and manual work for their operations.

This disconnect was most noticeable in the payroll and benefits sector. Even though companies like 1C and SAP have been around for more than 20 years, about 30% of SMBs still calculate payroll without the help of a third-party service.

There are several reasons why existing developers haven't made payroll for small businesses. First, SMBs are fragmented and difficult to access. Compared to the value they bring, the cost of servicing them has traditionally been too high to justify the effort if you can't sell them multiple products.

The lack of access to simple payroll and benefits tools has had a significant impact on the operational efficiency of SMEs and the well-being of their employees. But where there is a gap, there is an opportunity.

#### 2.2 What is Poluchka?

Poluchka (Paycheck) is state-of-the-art cloud-based software that helps micro, small and medium-sized businesses easily integrate, track, pay and support their employees.

Poluchka globally does three things:

1. Provides peace of mind for employers and employees regarding complex actions such as payroll, benefits, attendance and more.
2. Helps create a better work environment by focusing more on the partnership between employer and employee.
3. Creates opportunities for employees to thrive by helping to increase wages, and providing access to their hard earned money.

#### 2.3 Purpose of creation

The main thing to focus on is payroll, because it is the most pressing problem.

The goal of Poluchka is to help employers create a great place to work and build successful teams. And for employees, the purpose of the Poluchka is to help the individual become the primary focus of their financial well-being and their career

The name "Poluchka" embodies the company's mission to create a world where work makes life better and where everyone is "fairly rewarded" for the work they do.

#### 2.4 Salary

The payroll structure is complex. It involves managing multiple systems (taxes, bonuses, compensation, payments) in a reliable and compatible manner. To properly manage payroll, a business must determine which taxes are applicable to a particular employee (there are many options, usually determined by where the employee lives and works). 

The business must calculate the correct amount of tax, then determine how taxes are paid, which is just as complex a process. And then there are the references. Each tax referral requires a separate filing. There are many such documents and the forms are very different. Finally, the business must send payment to the employee after payroll or hand-deliver the money. 

Payroll is a product that must work because people depend on it. Poluchka must provide reliable, timely and accurate tax calculations, registrations and payments in order to gain the trust of customers.

The goal is to first address the basics of payroll and then expand it to more segments. This approach will build a stronger foundation and confirm that the product is truly easy to use and enjoyed by users.

#### 2.5 Tracking attendance

Attendance tracking allows an employer or manager to track employee work hours and attendance. It helps users with employee/task scheduling, time management, absence and vacation management, overtime tracking, and document management.

It saves money by electronically marking an employee's arrival and departure times, which reduces inaccurate time reports, marking for a colleague and overpayments.

Data accuracy leads to better payroll processing, and viewing employee schedules in real time helps improve overall productivity.

Key tracking features:

- Manage and track employee time off and calculate total attendance.
- Measuring the number of hours worked by an individual employee.
- Generating reports and analytics on hours worked and vacation usage.

Mobile compatibility makes the attendance tracking system accessible from any location and makes it easy to track the location of remote employees using GPS technology.

#### 2.6 A universal platform for people

It made sense to start with payroll and attendance tracking for two reasons. First, it is necessary for any business. Second, building a payroll architecture requires collecting and structuring a lot of data (employee name and address, start date, payroll methods, etc.). This structured data will help develop a payroll and attendance tracking kernel, as well as, expand around it a platform for people to help small and medium-sized businesses create great places to work.

One of the main drivers of this thinking has been a desire to give small and medium-sized businesses all the advantages, resources, tools and benefits that large companies have historically had. Historically, SMEs have existed on their own.

Poluchka has been a centralized source of reliable information for managing employees. Manual and time-consuming processes such as, creating job offer letters, onboarding a new employee and setting up software are automated. Once registered, the process of signing the offer is tracked and the necessary forms and plans are distributed. After adaptation, it is possible to track employee hours and calculate salaries.

#### 2.7 User experience

In addition to greatly increasing the efficiency of the processes, it is worth focusing on making sure that customers are happy with all aspects of the product. When a candidate receives an offer, it's like a wedding invitation rather than the typical paperwork. On payday, employees receive a celebratory email to which the employer can add a personal message. To all of this go the gamification elements, such as gaining experience, levels and achievements. All of this transforms what was once an exceptionally uninteresting experience into a more people-oriented experience in which employees are seen as valuable team members.

When it's time for payroll, a notification is sent to sign forms and send payment. A report is generated for a certain period of time, and an email is sent to the employer. All of this results in huge time savings for employers.

The experience with Poluchka is like communicating with a reputable partner, not just as another payroll tool. SMBs need a partner they can trust who also offers great service and great technology; Poluchka aims to be that partner.

## 3 Expanding capabilities

Looking ahead, we believe there are two major opportunities for Poluchka to build on the solid foundation described in point 2.

First, simply create more products for businesses and their employees. Because Poluchka is at the intersection of employees and employers, it is well positioned to launch new products for both parties. Poluchka can continue to make their lives easier, help employers do business better and help employees achieve their work goals. In time, Poluchka will be able to add hiring and job search capabilities within its own platform. On the employer side, Receipt can help address many other pain points, including further streamlining compliance and reporting, simplifying business finances and more.

The second major opportunity we see is embedded services and an open API to allow business software companies to offer payroll capabilities to their customers through APIs.

And that's just the beginning. Poluchka will be able to provide developers with APIs to embed their suite of people products into their own platforms as a complete infrastructure-as-a-service (IaaS) solution.

## Conclusion

We offered an automated system for simplified payroll and personnel management, but the really important thing was the understanding that people are the foundation of any business. People are what make small and medium-sized businesses special. With Poluchka, small and medium-sized businesses and the people who work in them have more opportunities to succeed than ever before.
