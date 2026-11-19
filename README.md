# PayFlow

A payment processing demo application, built in public to learn how reliable payment systems work.

> **Note:** PayFlow is an engineering case study, not a production payment service. It uses a simulated payment processor, so no real money is involved.

## About the project

Every day we click **Pay** and see "Payment successful" within seconds. PayFlow explores what actually happens in those few seconds, and how a system keeps money safe when things go wrong.

I'm building it one stage at a time, and writing an article about each stage: what I built, what I broke on purpose, and what I learned.

## What PayFlow demonstrates

- Payment creation and processing
- Payment lifecycle and transaction states
- Secure payment token handling
- Idempotency and duplicate payment prevention
- Double-entry ledger fundamentals
- Refund processing
- Handling payment timeouts and uncertain outcomes
- Automated testing of financial business rules
- Real payment gateway integration in test mode

## Tech stack

| Layer | Technology |
| --- | --- |
| Frontend | React |
| Backend | Java, Spring Boot |
| Database | MySQL |
| Payments | Simulated payment processor (real gateway in test mode in stage 9) |

## Roadmap

| Stage | Topic | Status |
| --- | --- | --- |
| 1 | Creating a payment and storing money safely | In progress |
| 2 | Payment lifecycle and transaction states | Planned |
| 3 | Secure payment token handling | Planned |
| 4 | Idempotency and duplicate payment prevention | Planned |
| 5 | Double-entry ledger | Planned |
| 6 | Refund processing | Planned |
| 7 | Timeouts and uncertain outcomes | Planned |
| 8 | Automated testing of financial business rules | Planned |
| 9 | Real payment gateway in test mode | Planned |

## Project structure (planned)

```
payflow/
├── backend/    # Java + Spring Boot API
└── frontend/   # React application
```

## Getting started

Setup instructions will be added once stage 1 is complete.

## Articles

1. [What really happens after you click Pay? Building PayFlow to find out](ADD-ARTICLE-LINK)

## Author

**[Durgesh More]**, software developer working with Java, Spring Boot and React.

- LinkedIn: [](www.linkedin.com/in/durgesh-more)
- Email: durgeshmore809@gmail.com

If you're building a product and need help with an MVP, a backend or REST API, or a payment integration, feel free to reach out.

## License

This project is licensed under the MIT License.
