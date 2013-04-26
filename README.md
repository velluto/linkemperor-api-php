# Linkemperor API

This library is used to access The Link Emperor API.

## Usage

Include the pho files and use it as follow:

    include('customers.php');
    include('vendors.php');
  
    # Customers
    $api = new LinkemperorCustomer("<api key>");
    $api->some_method();
  
    # Vendors
    $api = new LinkemperorVendor("<api key>");
    $api->some_method();

For details on the available operations, check documentation available on
http://www.linkemperor.com/api-documentation

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
