This project uses the omniauth-acclaim gem residing at https://github.com/brentkastner/omniauth-acclaim.

See it in action @ https://acclaim-oauth.herokuapp.com

## Installation

    $ git clone git@github.com:brentkastner/acclaim-oauth2-example.git
    $ bundle install
    $ rake db:create
    $ rake db:migrate
    $ ACCLAIM_ID=<app_id> ACCLAIM_SECRET=<acclaim_secret> rails s
    
You should then be able to go to http://localhost:3000/

## Contributing

1. Fork it ( http://github.com/brentkastner/acclaim-oauth2-example/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

