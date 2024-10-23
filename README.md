# Village Medical - Frontend Interview

![Village Medical](https://www.villagemd.com/hs-fs/hubfs/villagemd-logo-1.png?width=297&height=73&name=villagemd-logo-1.png)

## Introduction

This is a simple application that allows business owners to manage discounts for their customers. The app is built using React-Native, Expo amd react-native-paper.

## Features

- View Customer List
  - Business owners can see a list of their customers along with their yearly spend.
- Assign and Remove Discounts
  - Add or remove discounts for individual customers.
- Unassigned Discounts Page
  - View all discounts that have not been assigned to any customer.
- Discount Validation
  - When assigning discounts, the app validates the assignment based on specific business rules to ensure fairness and compliance.

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Task

#### Requesting Multiple Providers

[https://randomuser.me/api/?results=5](https://randomuser.me/api/?results=5)

#### Filter by nationality

[https://randomuser.me/api/?nat=us,gb](https://randomuser.me/api/?nat=us,gb)

#### Filter by gender

[https://randomuser.me/api/?gender=female](https://randomuser.me/api/?gender=female)

#### Pagination

[https://randomuser.me/api/?page=3&results=10&seed=abc](https://randomuser.me/api/?page=3&results=10&seed=abc)

#### API Errors

```json
{
  "error": "There was an error"
}
```

### Screenshots

![Customer List](./customer-page.png)
![Customer Detail](./customer-detail-page.png)