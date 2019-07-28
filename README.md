## VendingMachine


### How to use

````
$ irb
require './lib/vending_machine'
machine = VendingMachine.new

machine.stock_info
machine.store Drink.milk
machine.store Drink.water

machine.insert 100
machine.insert 500

machine.total
machine.refund

machine.purchasable_drink_names
machine.purchasable? :milk
machine.purchasable? :water

machine.purchasable_drink_names

machine.sale_amount

exit
````
