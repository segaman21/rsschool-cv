# Sergey Rudman

## Contact Info:
- ### email: Sergey02047747@gmail.com
- ### phone number: +375 33 6447685
- ### telegram:[@sega_rudman](https://t.me/sega_rudman)

## Skills:
- ### Java
- ### Kotlin

## Code examples:

```
 class NetworkModule {
    val json = Json {
       isLenient = true
        prettyPrint = true
        ignoreUnknownKeys = true
        coerceInputValues = true
    }
    private val baseUrl = "https://api.thecatapi.com/v1/"
    val contentType = "application/json; charset=utf-8".toMediaType()}
    fun provideApi(): CatsApi {
        val retrofit = Retrofit.Builder()
            .baseUrl(baseUrl)
            .addConverterFactory(json.asConverterFactory(contentType))
            .build()
        return retrofit.create(CatsApi::class.java)
    }
 }
```
## Experience:

Junior Android Developer

## Education:

2014-2018 Belarusian State University of informatics and radioelectronics

## English:

English level A2
