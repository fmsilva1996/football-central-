# Football Central

<p align="center">
  <img src="assets/logo.png" width='300'/>
</p>

A desktop web application that allows users to keep up with latest football news and results. What sets Football Central apart from other apps like it is its predictions functionality, where using an algorithm it provides users with predictions for a given match.

Check out the live app: https://www.footballcentral.xyz/

**Please Note:** The News API does not provide free access outside of localhost, therefore all news sections in the live app will be empty.

## Screenshots

<p align="center">
  <img src="assets/total-football.gif" />
</p>

## Getting Started

1. Clone the repo and open in your code editor of choice

```
git clone https://github.com/fmsilva1996/football-central.git
```

2. Install all required dependencies

```
npm install
```

3. Create a .env file with the following variables:

```
REACT_APP_NEWS_API_KEY=YOUR_API_KEY_HERE
REACT_APP_FOOTBALL_API_KEY=YOUR_API_KEY_HERE
REACT_APP_FOOTBALL_API_HOST=YOUR_API_HOST_HERE
```

4. Start application on localhost:

```
npm run start
```

5. Enjoy!

## Built With

- [React](https://reactjs.org/) - A JavaScript library for building user interfaces
- [React Router](https://reactrouter.com/web/guides/quick-start) - A collection of navigational components for your React applications
- [Football API](https://www.api-football.com/) - All football data
- [News API](https://newsapi.org/) - All news data

## Observations

### Room For Improvement

- The CSS could be modularized more, maybe experiment with Styled Components 💅
- Pull out helper functions and make use of useCallback to reduce load on each rerender
- Solution to cache data, rather than having to rely on paid APIs for every request

### Looking to the Future

- Adopt a mobile first design pattern in future projects
- Extensive testing (>70% Coverage) with Jest and Jasmine
- Server rendering with Next.js?
- Explore state management solutions with Redux
- Get comfortable with CSS grid and thank me later!

## Contributing

Improvements are welcome 🙂

Fork the repo and do your thing. Push to your fork and submit a pull request.

## Author

Francisco Silva - [Github](https://github.com/fmsilva1996) - [LinkedIn](https://www.linkedin.com/in/fmsilva1996/)

## License

This project is licensed under the MIT License.
