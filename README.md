<form-directive form="form" class="ng-isolate-scope ng-scope">
   ...
   <form name="myForm" id="myForm">
      ...
      <div ng-repeat="field in form.fields">
         <field-directive field="field">
            ...
         </field-directive>
      </div>
   </form>
