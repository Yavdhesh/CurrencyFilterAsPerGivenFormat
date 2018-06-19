# CurrencyFilterAsPerGivenFormat

Namastey hello everyone,

This code provides us a functionality to format any currency.
All we have to do is to provide the currency format and any amount.

For example :
 we call the API 
formatter(inputFromUser,format,currencySeparator,decimalSeparator,roundOff)

where inputFromUser= amount you want to format
      format="##,##,###@,@.@3"; #you may change the format to "##,###,###@,@.@3";
      currencySeparator = delimiter that we want to use for the inputProvided (for the current example it is ',' read character between           first @,@)
      decimalSeparator= character which is to be used as a decimal separator (read second @.@)
      roundOff=  after decimal delimiter the number of digits that you want to show.
      
A format like "##,##,###@,@.@3" will give us output as 1,00,00,000.000
A format like "##,###,###@,@.@3" will give us output as 10,000,000.000
A format like "##,###,###@.@,@2" will give us output as 10.000.000,00


