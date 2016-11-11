# customDirectives
</br>
Accordion (Made Pretty)
</br>
</br>
<a href="https://brendancopley.github.io/customDirectives/custom-accordion-ui-bootstrap/" target="_blank">Example DEMO</a>
</br>
</br>
What Makes This Custom Directive Great?
</br>
<p>It's actually very simple, go into the sourceapp.js file and you'll see I've copied the ui-bootstrap accordian template so you can use the same structure of <code>'uib-accordion'</code> as you've always used without having to remember a new element name to use each time.</p> 
</br>
How can I style the Accordion?</br>
<p>You can style the accordion by using the <code>style.css</code> file or the <code>style.scss</code> file if you prefer to use <b>SASS</b>. In the file you'll see <code>.panel-open {
  color: #28acb3; }</code> or the mixin <code>@include activeColor1();</code> just simply adjust the color to the color of your choice. Also you can use custom CSS ids like <code>id="anything"</code> and style your accordion headings differently in the same <code>uib-accordion</code> . Just remember to add <code>.panel.panel-open</code> after the id in your css file to do that.</p>
</br>
How can I have the first panel closed or open? </br>
<p>That's really simple just include the follow from in my <code>soureapp.js</code> file the angularjs code under the controller into your controller: </br></br><code>$scope.menuStatus = [   { isOpen : true     },<br>
                        { isOpen : false    }, <br>
                        { isOpen : false    } ]<br><br>
						</code> Then remember to add <code>is-open='menuStatus[0].isOpen'</code> to your <code>'div uib-accordion-group'</code></br>
						Just edit the index.html file and you'll see how I have my <code>'uib-accordion-heading'</code> and just copy that.</p>
Where can I checkout more custom directives you've done? </br>
<p>stay tuned to my github <a href="https://github.com/brendancopley">https://github.com/brendancopley</a> and my webiste: <a href="http://brendancopley.com">brendancopley.com</a></p>
