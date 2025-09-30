---
alwaysApply: true
---

# Naming Conventions Guide

## Core Naming Principles
- **MANDATORY**: Use clear, descriptive, and consistent naming conventions
- **File naming**: Use kebab-case for files (e.g., `user-profile.component.ts`, `api-client.service.ts`)
- **Variable naming**: Use camelCase for variables and functions (e.g., `userProfile`, `getUserData`)
- **Class naming**: Use PascalCase for classes and interfaces (e.g., `UserProfile`, `IDatabaseService`)
- **Constant naming**: Use UPPER_SNAKE_CASE for constants (e.g., `API_BASE_URL`, `MAX_RETRY_ATTEMPTS`)
- **Avoid abbreviations**: Use full words instead of abbreviations (e.g., `userProfile` not `usrProf`)
- **Be descriptive**: Names should clearly indicate purpose and context

## Specific Naming Patterns

### Boolean Variables and Functions
- **Prefix with `is`, `has`, `can`, `should`, `will`**: `isActive`, `hasPermission`, `canEdit`, `shouldValidate`, `willExecute`
- **Avoid negative prefixes**: Use `isEnabled` instead of `isNotDisabled`
- **Be explicit**: `isUserLoggedIn` instead of `loggedIn`
- **Functions returning booleans**: `isValid()`, `hasAccess()`, `canPerform()`

### ID and Identifier Handling
- **Use `Id` suffix**: `userId`, `productId`, `orderId`
- **Database IDs**: `primaryKeyId`, `foreignKeyId`
- **Temporary IDs**: `tempId`, `sessionId`
- **Composite IDs**: `userId_productId`, `orderId_itemId`
- **Avoid generic names**: Use `customerId` instead of just `id`

### Collections and Arrays
- **Use plural forms**: `users`, `products`, `orders`
- **Be specific**: `activeUsers` instead of `users`, `pendingOrders` instead of `orders`
- **Index variables**: `userIndex`, `itemIndex`, `currentIndex`
- **Count variables**: `userCount`, `totalItems`, `remainingSlots`

### Functions and Methods
- **Use verb prefixes**: `getUser()`, `createOrder()`, `updateProfile()`, `deleteItem()`
- **Be action-oriented**: `calculateTotal()`, `validateInput()`, `processPayment()`
- **Async functions**: `fetchData()`, `loadContent()`, `saveChanges()`
- **Event handlers**: `onClick()`, `onSubmit()`, `onError()`, `handleClick()`

### Configuration and Settings
- **Use descriptive prefixes**: `config`, `settings`, `options`, `params`
- **Examples**: `apiConfig`, `userSettings`, `displayOptions`, `requestParams`
- **Environment variables**: `ENV_`, `PROD_`, `DEV_` prefixes (e.g., `ENV_DATABASE_URL`)

### Error and Exception Handling
- **Use `Error` suffix**: `ValidationError`, `NetworkError`, `AuthenticationError`
- **Exception classes**: `UserNotFoundException`, `InvalidInputException`
- **Error codes**: `ERROR_CODE_`, `ERR_` prefixes (e.g., `ERROR_CODE_INVALID_TOKEN`)

### Status and State Variables
- **Use descriptive status names**: `orderStatus`, `userState`, `connectionState`
- **Enum-like values**: `PENDING`, `COMPLETED`, `FAILED`, `ACTIVE`, `INACTIVE`
- **State transitions**: `fromState`, `toState`, `previousState`, `nextState`

### API and Service Naming
- **Service classes**: `UserService`, `PaymentService`, `NotificationService`
- **API endpoints**: `getUserById`, `createUser`, `updateUserProfile`
- **Repository pattern**: `UserRepository`, `OrderRepository`
- **Controller classes**: `UserController`, `OrderController`

### UI Components and Elements
- **Component names**: `UserProfile`, `OrderSummary`, `PaymentForm`
- **CSS classes**: Use kebab-case (e.g., `user-profile`, `order-summary`)
- **Element IDs**: Use kebab-case (e.g., `user-profile-form`, `submit-button`)
- **Event names**: `user-selected`, `order-completed`, `payment-processed`

### Database and Data Models
- **Table names**: Use snake_case (e.g., `user_profiles`, `order_items`)
- **Column names**: Use snake_case (e.g., `created_at`, `updated_at`, `user_id`)
- **Model classes**: Use PascalCase (e.g., `UserProfile`, `OrderItem`)
- **Migration files**: Use descriptive names (e.g., `create_user_profiles_table`)

### Testing and Test Files
- **Test files**: Use descriptive names (e.g., `user-service.test.ts`, `payment-integration.spec.ts`)
- **Test functions**: Use descriptive names (e.g., `shouldReturnUserWhenValidIdProvided`)
- **Mock objects**: Use `Mock` prefix (e.g., `MockUserService`, `MockDatabase`)
- **Test data**: Use descriptive names (e.g., `validUserData`, `invalidEmailData`)

## Language-Specific Conventions

### JavaScript/TypeScript
- **Modules**: Use camelCase for module names (`userService.js`)
- **Namespaces**: Use PascalCase (`MyApp.Models`)
- **Interfaces**: Prefix with `I` (`IUserService`, `IDatabaseConnection`)
- **Enums**: Use PascalCase (`OrderStatus`, `UserRole`)

### Python
- **Modules**: Use snake_case (`user_service.py`)
- **Classes**: Use PascalCase (`UserService`)
- **Functions**: Use snake_case (`get_user_data()`)
- **Constants**: Use UPPER_SNAKE_CASE (`MAX_RETRY_COUNT`)

### Java
- **Packages**: Use lowercase (`com.company.project`)
- **Classes**: Use PascalCase (`UserService`)
- **Methods**: Use camelCase (`getUserData()`)
- **Constants**: Use UPPER_SNAKE_CASE (`MAX_RETRY_COUNT`)

### C#
- **Namespaces**: Use PascalCase (`MyCompany.MyProject`)
- **Classes**: Use PascalCase (`UserService`)
- **Methods**: Use PascalCase (`GetUserData()`)
- **Properties**: Use PascalCase (`UserName`)

## Best Practices

### Consistency
- **Maintain consistency** within the same project
- **Follow team conventions** when working in a team
- **Use linters** to enforce naming conventions automatically
- **Document exceptions** when deviating from standard conventions

### Readability
- **Prioritize clarity** over brevity
- **Use meaningful names** that explain intent
- **Avoid cryptic abbreviations** unless they're widely understood
- **Consider future developers** who will maintain the code

### Context Awareness
- **Consider the domain** when choosing names
- **Use domain-specific terminology** when appropriate
- **Maintain consistency** with existing codebase patterns
- **Adapt conventions** to the specific technology stack

## Automatic Reminder
- These naming conventions must be applied to ALL code development, without exception
- Always consider readability and maintainability when choosing names
- When in doubt, choose the more descriptive option
- Regularly review and refactor names to improve clarity