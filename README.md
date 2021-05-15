## Created for Revolut API integration

### Requirements:
- Send report if favourites list is increasing or decreasing
- Provide exchange from PLN to USD in good specific course 
  
  I've checked at pricing page with `Metal` plan and there wasn't more about it. 
  I think there might be possibility on that plan (I didn't checked it yet), but this app would do the exchange for me. 
  I can just do other stuff. It would have include more functionality for sure :)

## Instalation
#### Build container:
docker build -t rust-revolut -f ./Dockerfile .

#### Run container:
docker run -p 8000:8000 rust-revolut

### Author
Marcin Szostak <luxurno@luxurno.com>

### Author notes:
It's my first idea on project for Rust lang and advanced coding. Please be forgiving.
Feel free to contribute, maintain or add functionality.
Please just add Requirements steps or ideas to include to make.
Also feel free to put your author info :)

