<h2 align="left">weather.guru</h2>

###

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="150" alt="javascript logo"  />
</div>

## Installation

```
git clone https://github.com/kenjitheman/weather.guru
```

## Usage
- you have to have your openweather api key to use it
- paste your api key in api.js file (js folder)

```bash
export const getWeatherData = async (city) => {
    try {
        const response = await fetch(`https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=633f3f4df62e35d09ia55b1148165&lang=en&units=metric`);      // example api key (have to be your openweather api key | API キーの例 (openweather である必要があります)

        return await response.json();

    } catch (error) {
        console.error(error);
    }
};
```

## License

- [MIT](https://choosealicense.com/licenses/mit/)
