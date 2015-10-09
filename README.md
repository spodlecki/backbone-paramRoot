## Backbone JS

JavaScript from [backbone-rails](https://github.com/codebrew/backbone-rails/blob/master/vendor/assets/javascripts/backbone_rails_sync.js) gem.

## Usage

```coffeescript
class User extends Backbone.Model
  paramRoot: 'user'
```

What this JS will do is send the POST / PUT with a container `user`

```
{
  user: {
    email: 'foo@baz.com'
  }
}
```

## Credit

Full credit goes to the [backbone-rails gem](https://github.com/codebrew/backbone-rails)