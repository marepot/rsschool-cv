# __Margarita Sopot__

### Contacts
---
__GitHub:__ [marepot](https://github.com/marepot)  
__E-mail:__ margo.sopot@mail.ru  
__Telegram:__ @marepot  
__Discord:__ @marepot  



### About Me
---
I am young specialist who whants to increase knowlege in web development.



### Skills
---
__Programming languages and Technologies:__ JavaScript, HTML, CSS, NodeJS, PHP  
__Databases:__ SQLite, Microsoft SQL Server  
__OS:__ Windows, Linux (Ubuntu)  

### Code Examples
---
    db.chart_data(city_id, ['temp', 'dt', 'pressure', 'humidity', 'dew_point', 'uvi', 'wind_speed'], function (data_chart) {
    var city_id = cities_id();
    if (city_id == null) {
        city_id = 625144;
        data_chart = data_chart.map(function (с) {
            с.temperature = с.temp;
            с.date = new Date(с.dt * 1000);
            return с;
    });
    } else {
        data_chart = data_chart.map(function (с) {
            с.temperature = с.temp;
            с.date = new Date(с.dt * 1000);
            return с;
        });
     }
    res.json(data_chart);
    });

### Education
---
__2017-2021__ International Sakharov Environmental Institute of Belarusian State University, Minsk, Belarus, Faculty of Environmental Monitoring  

__Specialty:__ Information Systems and Technologies (in public health)  

__Qualification:__ Software Engineer  


### Languages
---
* Russian (native)
* Belorussian (native)
* English (B2)
