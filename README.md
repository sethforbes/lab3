# lab3
# The modular cash register

# First define our functions:

# Determine tax rate for this customer
# asks customer whether she is tax exempt and returns
# tax rate of 5% or 0% accordingly
# eventually this could maybe handle tax rates for
# various locations
def get_tax_status():
    pass # add code for this function here
	
# Get a list of items from the user
# returns the list (not the total)
pass # this function needs to be defined here

# function to print out our final report
# takes two parameters for tax rate and subtotal
# prints subtotal, tax, and total
# does not return anything
def print_report(tax_rate,subtotal):
    pass # add code for this function here

#############################################################

# Main part of the code

# Print cash register receipt and handle tax exempt customers

tax_r = get_tax_status()	# get tax rate for customer

items = get_items()		# get items
subtot = sum(items)		# add them up

print_report(tax_r,subtot)	# print the report

