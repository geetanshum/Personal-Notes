### To create a form from model
```
class AbcForm(ModelForm):
    class Meta:
        model = FormModel
        fields =('name','age','dob','address')
        widgets = {'dob':DateInput(attrs={'type':'date'}),
        'address':Textarea(attrs={'rows':4,'cols':20})}
```
