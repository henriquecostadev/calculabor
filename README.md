# Calculabor

![alt](./images/logo1024x500.png)

Este aplicativo foi desenvolvido para facilitar o cálculo do valor do salário por hora, mês, dia e ano de forma simples e eficiente. Além disso, oferece recursos avançados para simulações de salário em diferentes moedas, como dólar e euro, e também permite simulações para regime de Pessoa Jurídica (PJ).

## Plataformas disponíveis

- Android: [PlayStore](https://play.google.com/store/apps/details?id=br.com.calculabor)
- IOS: AppStore, em breve...

## Principais Recursos

- Cálculo Preciso: Obtenha o valor do salário em diferentes períodos de tempo de maneira rápida e precisa.
- Conversão de Moeda: Simule seu salário em dólar, euro e outras moedas para avaliar seu valor em diferentes contextos econômicos.
- Simulação PJ: Compare valores de salários com base em regime de Pessoa Jurídica para tomar decisões mais informadas.

Sinta-se à vontade para contribuir, abrir problemas ou sugerir melhorias para aprimorar essa ferramenta e torná-la ainda mais útil!

![alt](./images/screen01.gif)
![alt](./images/screen02.gif)
![alt](./images/screen03.gif)
![alt](./images/screen04.gif)

# Dev

Welcome to Calculabor! This application is built using React Native, a powerful framework for creating cross-platform mobile applications.

Unfortunately we still working on the unit testes and some refactories in the code to share the whole code properly shareable. But here you can taste a little bit about what is coming soon:

![alt](./images/flow-diagram.png)

## Development

- [React Native](https://reactnative.dev/): A JavaScript framework for building natively rendered mobile applications for iOS and Android.
- [TypeScript](https://github.com/microsoft/TypeScript): A typed superset of JavaScript that enhances code quality and development experience.
- [Node.js](https://github.com/nodejs/node): Used for server-side logic and package management.
- [Yarn](https://github.com/yarnpkg/berry): Package managers to handle dependencies and streamline the development process.

## UI/UX

- [React Navigation](https://github.com/react-navigation): For creating smooth navigation within the app.
- Styled Components with CSS: Used for styling components.

## Backend & APIs

- [Axios](https://github.com/axios/axios): For RESTful APIs, communication with the backend server, making HTTP requests to APIs.
- [react-native-sqlite-storage](https://github.com/andpor/react-native-sqlite-storage): A SQLite local database implementation for React Native applications.

## Testing

To ensure that the code do what it should do and preventing not breaking anything in the next maintenances, unit and integration tests were implemented in three steps:

- Snapshot: to ensure that the app is rendering correctly, like the colors and shapes of the components.
- User interactions: to ensure that the app behaves correctly when interacted with by a user.
- Component: to ensure that the local hooks, services and repositories are working as expected.

## Design Patterns

- MVVM (Model-View-ViewModel): Design pattern to separate the concerns of the user interface, business logic, and data representation improving the app's quality, maintainability and extensibility.
- BEM (Block Element Modifier): A popular naming convention that is designed to be modular and reusable. It consists of three parts: the block, the element, and the modifier. The block is the main component, the element is a part of the block, and the modifier is a variation of the element. For example, a button block might have an element called `.button__label` and a modifier called `.button__isActive`.

## Additional Tools

- [Git](https://git-scm.com/): Version control system for collabor`ation and code management.
- [ESLint and Prettier](https://github.com/prettier/eslint-config-prettier): Code linting and formatting tools ([esbenp.prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)) for maintaining code quality and consistency.

## Contribution

Contributions to Calculabor are welcome! To contribute:

1. Fork this repository.
2. Create a new branch:

```bash
git checkout -b feature/awesome-feature
```

3. Commit your changes

```bash
git commit -am 'Add some awesome feature'
```

4. Push to the branch

```bash
git push origin feature/awesome-feature
```

5. Create a pull request.

## Contact

For any inquiries or support, contact henrique8619@gmail.com .
