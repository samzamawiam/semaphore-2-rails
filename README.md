# README

```
bundle install
npm i -g yarn (if you don't have it already)
yarn install
bundle exec rails db:create (db steps just needed to make rails happy at boot, nothing stored in DB)
bundle exec rails db:migrate
bundle exec rspec
```

Should run the `spec/system/basic_spec.rb` file.

Use the following command in a pry session to see the JS errors
`page.driver.browser.manage.logs.get(:browser)`
