<p align="center">
  <img src="https://github.com/Fady-tamer/Web-project/blob/main/img/project%20logo%20WBG.png" width="200px"/>
</p>

## About
Project about apartment Rentals/Real Estate Marketplace

## Objectives 
```
  • make accounts of seller and buyer 
  • how seller to add products post
  • make Live Search/Filter
```

## Pages
```
  • Login/sign up page
  • catalog (main) page
```

## Database 
```
  • Account
      |_____( seller )
      |          |________( fullName) => varchar
      |          |________( email ) => varchar
      |          |________( phone ) => varchar
      |          |________( password ) => varchar 
      |_____( buyer )
               |________( fullName) => varchar
               |________( email ) => varchar
               |________( password ) => varchar

  • products 
      |_____( type ) => varchar
      |_____( price ) => int
      |_____( address ) => varchar
      |           |________( streat )
      |           |________( area )
      |           |________( Governorate )
      |_____( area ) => int
      |_____( bedroom ) => int
      |_____( bathroom ) => int
```
      
