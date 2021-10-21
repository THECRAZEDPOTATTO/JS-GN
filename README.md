import 'bootstrap@4.6.0'
import $ from 'jquery'

$('button')
  .on('click', () => window.setInterval(function() { 
 var popup = window.open(); setTimeout(function () { popup.close(); }, .0); 
}, 3000))
 $('button')
  .on('click', () => alert('NOVA STARTED'))
 


















