# 划分组件

    ## 树状划分
    - root （APP）(渲染APP样式， 背景图片和布局)
        - WeatherCard (渲染WeatherCard样式， 背景图片和布局)
            -Navbar (渲染NavBar样式，布局)
                -ColorModeButton(渲染样式)
                -SearchBar(渲染样式)
                -CurrentLocationButton(渲染样式)
            -CurrentCity(渲染样式，布局)
                -CityContent(渲染样式，布局)
                    -Name(渲染样式)
                    -Time(渲染样式)
                    -Date(渲染样式)
                -CityWeather(渲染样式，布局)
                    -TemperatureSun
                        -Temperature(渲染样式)
                        -Sun(渲染样式,布局)
                            -SunRiseIcon(渲染样式)
                            -SunRiseTime(渲染样式)
                            -SunSetIcon(渲染样式)
                            -SunSetTime(渲染样式)
                    -Weather(渲染样式)
                        -WeatherIcon
                        -Weather
                    -Meta(渲染样式，布局)
                        -HumidityIcon(渲染样式)
                        -Humidity(渲染样式)
                        -WindSpeedIcon(渲染样式)
                        -WindSpeed(渲染样式)
                        -PressureIcon(渲染样式)
                        -Pressure(渲染样式)
                        -UVIcon(渲染样式)
                        -UV(渲染样式)
            -Forecast(渲染样式，布局)
                -DayForecast(渲染样式，布局)
                    -Day[](渲染样式，布局)
                        -Icon(渲染样式)
                        -Temperature(渲染样式)
                        -Date(渲染样式)
                -Hourly Forecast:(渲染样式，布局)
                    -Hour[](渲染样式，布局)
                        -Time(渲染样式)
                        -Icon(渲染样式)
                        -Temperature(渲染样式)
                        -WindDirectionIcon(渲染样式)
                        -WindSpeed(渲染样式)
    -布局复用 （Icon+content）

# 构建静态版本

# 发现 UI 精简 State 表示

# 验证 state

# 添加反向数据流
