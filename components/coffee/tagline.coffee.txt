$ = require 'jquery'

do fill = (item = 'The Creative minds in Art') ->
  $('.tagline').append "#{item}"
fill