Usage
=====

Submodule this into your Rails app
In your ApplicationController add the following:

```ruby
class ApplicationController < ActionController::Base
  ...
  include Render404
end
```
