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

| Command | Description |
| --- | --- |
| ci_model | Model namespace |
| ci_controller | Controller namespace |
| ci_load_helper | Load helper sintax |
| ci_view | Echo CI view |
| ci_new_renderer | New View Renderer |
| ci_render_section =ci_log |  Logging information> Render section view |
| ci_extend_layout | Extend layout (insert view into a layout) |
| ci_view_section | View section (content within a view that extends a layout) 
| ci_view_include | View include |
| ci_get_locale | Get Locale |
| load_database | Load the Database |
| ci_db_query | Query |
| ci_query_result | Get the query result as object |
| ci_query_result_array | Get the query result as array |
| ci_query_row | Get the query result as row (object) |
| ci_query_row_array | Get the query result as row (array) |
| ci_addroute | Add Route |
| ci_addrouteclosure | Add Route With Closure |
| ci_anchor | Anchor Link |
| ci_getCookie | Return any data from $_COOKIE |
| ci_getGet | Return any data from $_GET |
| ci_getPost | Return any data from $_POST |
| ci_getServer | Return any data from $_SERVER |
| ci_getVar | Return any data from $_GET, $POST, or $_COOKIE |
| ci_isajax | Check if request is ajax |
| ci_iscli | Check if request is CLI |
| ci_issecure | Check if request is HTTPS |
| ci_log | Logging information |
| ci_filter | Create a new filter class | 
| ci_db_conn | Create a new database connection | 
| ci_entity | Create a new Entity class | 
| ci_cache | Save into the cache for x minutes | 
| ci_getcache | Grab an instance of the cache engine directly through the Services class | 

# Contributors

* [Marco Monteiro](https://marcomonteiro.net)
* [haerunn](https://github.com/haerunn)