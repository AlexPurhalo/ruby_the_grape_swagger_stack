<h2>Installation</h2>
<ul>
    <li>$ <strong>git clone https://github.com/AlexPurhalo/ruby_the_grape_swagger_stack.git</strong></li>
    <li>$ <strong>cd ruby_the_grape_swagger_stack</strong></li>
    <li>$ <strong>rbenv install 2.2.3</strong> / $ <strong>rvm install 2.2.3</strong></li>
    <li>$ <strong>rbenv shell 2.2.3</strong> / $ <strong>rvm use ruby-2.2.3</strong></li>
    <li>$ <strong>gem install foreman</strong></li>
    <li>$ <strong>bundle exec rake db:create_migration NAME=create_table_notes</strong></li>
    <li>$ <strong>rake db:migrate</strong></li>
</ul>
<br>
<h2>Progress</h2>
<ul>
    <li>$ <strong>foreman start</strong></li>
    <li>checkout: <strong>http://localhost:5000/swagger-ui</strong></li>
    <li>$ <strong>bundle exec rake -T</strong></li>
</ul>