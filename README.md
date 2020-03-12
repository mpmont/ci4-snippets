Codeigniter 4 Snippets for Sublime Text 2/3
=======================

[![Codeigniter](https://img.shields.io/badge/Codeigniter-v4.0-orange.svg)](http://codeigniter.com/)

This is a [Sublime Text][sublime] package which includes a bunch of handy snippets for doing Codeigniter 4 framework development.

### Easy installation ###

If you have the [Package Control][package_control] package installed, you can install Codeigniter framework Snippets from inside Sublime Text itself. Open the Command Palette and select "Package Control: Install Package", then search for Codeigniter 4 framework Snippets.

### Manual installation ###

If you haven't got Package Control installed you will need to make a clone of this repository into your packages folder **(Preferences > Browse packages...)**, like so:

 > `git clone https://github.com/mpmont/ci4-snippets ci4-snippets`

If you find error or whatever just fork it and send me a pull request.

[sublime]: http://www.sublimetext.com/
[package_control]: https://packagecontrol.io/


## Avaiable snippets

1. ci_model => Model namespace
2. ci_controller => Controller namespace
3. ci_load_helper => Load helper sintax
4. ci_view => Echo CI view
5. ci_new_renderer => New View Renderer
6. ci_render_section =ci_log =>  Logging information> Render section view
7. ci_extend_layout => Extend layout (insert view into a layout)
8. ci_view_section => View section (content within a view that extends a layout)
9. ci_view_include => View include
10. ci_get_locale => Get Locale
11. load_database => Load the Database
12. ci_db_query => Query
13. ci_query_result => Get the query result as object
14. ci_query_result_array => Get the query result as array
15. ci_query_row => Get the query result as row (object)
16. ci_query_row_array => Get the query result as row (array)
17. ci_addroute => Add Route
18. ci_addrouteclosure => Add Route With Closure
19. ci_anchor => Anchor Link
20. ci_getCookie => Return any data from $_COOKIE
21. ci_getGet => Return any data from $_GET
22. ci_getPost => Return any data from $_POST
23. ci_getServer => Return any data from $_SERVER
24. ci_getVar => Return any data from $_GET, $POST, or $_COOKIE
25. ci_isajax => Check if request is ajax
26. ci_iscli => Check if request is CLI
27. ci_issecure => Check if request is HTTPS
28. ci_log => Logging information

# Contributors

[Marco Monteiro](https://marcomonteiro.net)
