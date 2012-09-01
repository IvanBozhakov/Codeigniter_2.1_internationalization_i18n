// URI like '/en/about' -> use controller 'about'
$route['^(en|de|fr|nl)/(.+)$'] = "$2";

// '/en', '/de', '/fr' and '/nl' URIs -> use default controller
$route['^(en|de|fr|nl)$'] = $route['default_controller'];  a