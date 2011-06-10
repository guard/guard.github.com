# More info at https://github.com/guard/guard#readme

guard 'bundler' do
  watch('Gemfile')
end

guard 'ego' do
  watch('Guardfile')
end

guard 'pow' do
  watch('.rvmrc')
  watch('config.ru')
end

guard 'haml', :output => '.' do
  watch(/^.+\.html\.haml$/)
end

guard 'sass', :output => 'public/stylesheets' do
  watch(/^.+\.css\.sass$/)
end

guard 'coffeescript', :output => 'public/javascripts' do
  watch(/^.+\.js\.coffee$/)
end

guard 'jammit' do
  watch(/^public\/javascripts\/.+\.js$/)
  watch(/^public\/stylesheets\/.+\.css$/)
end

guard 'livereload' do
  watch(/^.+\.html$/)
  watch(/^public\/assets\/.+\.(css|js)$/)
end
