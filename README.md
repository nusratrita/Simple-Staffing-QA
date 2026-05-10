# Simple Staffing — QA Testing Showcase

Manual QA work on **Simple Staffing**, a workforce management and on-demand staffing platform built for an **Atlanta-based client** at **Right Brain Solution Ltd**.

> The product is proprietary client work. This repo is a public summary of the QA scope, tools, and methodology I followed.

---

## About the Product

Simple Staffing connects **clients** who need short-term workers with **candidates** looking for paid jobs, and gives the **admin team** end-to-end visibility into every shift.

### Platforms
- **Web** — full client + admin experience
- **Mobile (Android & iOS)** — candidate-facing app for browsing, applying, and clocking in

### User Roles
- **Client** — posts jobs (date, time, hourly rate), reviews applications, hires candidates, monitors live work, approves payments
- **Candidate** — browses jobs, applies, starts/stops the shift timer from anywhere on mobile, gets paid
- **Admin** — oversees all clients, candidates, jobs, invoices, and payroll from a central dashboard

### Key Features Tested
- Job creation with scheduling (date / time / hourly amount)
- Candidate application & selection flow
- Live shift time-tracking via mobile (start/stop timer from any location)
- Real-time work monitoring for clients
- Invoice generation and management
- Payroll system with payment processing
- Admin oversight of every client, candidate, and shift

---

## My Role

**Manual QA Tester** — owned the testing of every release across web and mobile for the duration of the engagement (~6–12 months), including post-launch support directly with the client.

### What I covered
- **Web** — client and admin portals across major browsers
- **Android & iOS apps** — candidate flows, GPS-based timer, push notifications, payments
- **Cross-platform consistency** — making sure web and mobile stayed in sync
- **Payment & payroll** — invoice generation, payroll runs, payment gateway flows
- **Post-delivery support** — communicated directly with the Atlanta client, gathered requirements, reproduced reported issues, verified fixes, and signed off on hotfixes

---

## Testing Toolkit

| Area | Tools |
|------|-------|
| Bug tracking & task management | Trello |
| Test case management | TestRail, Excel |
| API testing | Postman |
| Cross-browser & device testing | BrowserStack |
| Real-device testing | Physical Android & iOS devices |
| Communication | Direct client calls, email, screen-sharing for repro |

---

## Testing Types Performed

- **Functional testing** — every new feature against acceptance criteria
- **Smoke testing** — quick health checks before each build promotion
- **Regression testing** — full pass before releases to catch side-effects
- **Cross-browser compatibility** — Chrome, Firefox, Safari, Edge
- **Device & OS compatibility** — multiple Android and iOS versions, varied screen sizes
- **Payment & payroll flow testing** — end-to-end invoice → payroll → payment verification
- **UAT / release sign-off** — final acceptance gate before production
- **Post-release support testing** — reproducing client-reported issues, validating hotfixes, requirement clarification with the client

---

## Sample Areas of Focus

- **Time-tracking accuracy** — start/stop timer from various locations, network drops, app backgrounded
- **Job-state transitions** — created → applied → hired → in-progress → completed → invoiced → paid
- **Role-based access** — making sure clients, candidates, and admins only saw what they should
- **Edge cases on payroll** — overlapping shifts, partial hours, rate changes mid-job
- **Notification reliability** — push, email, and in-app alerts across job lifecycle events
- **Data integrity** — invoice totals matching tracked hours × hourly rate

---

## Contact

**Nusrat Rita** — QA / SDET
- Email: nusratrita00@gmail.com
- GitHub: [@nusratrita](https://github.com/nusratrita)

---

*Simple Staffing is proprietary client software developed by Right Brain Solution Ltd. This repository is a personal portfolio summary and contains no source code or confidential client data.*
