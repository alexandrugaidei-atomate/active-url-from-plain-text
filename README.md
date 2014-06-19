Active url from plain text
===============

Small Codeigniter helper for create active links from plain url in any text.

The code is released under an MIT license.

Usage
-----

```php
    public function __construct(){
        parent::__construct();

        $this->load->helper('activeurl');
    }
    
    public function index(){
    
      $text = "Some text with link http://alexandru.master.pro.md";
      echo activeUrl($text);
    
    }
    
```

Result: 
-----
Some text with link http://alexandru.master.pro.md
