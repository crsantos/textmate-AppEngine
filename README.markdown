#AppEngine Textmate bundle

The missing Python AppEngine Bundle, feel free use and contribute.

## Models
* `model` / `poly` - The standard AppEngine Models for DB.

### Properties
* `sp` - StringProperty
* `blp` - BlobProperty
* `dtp` - DateProperty
* `dttp` - DateTimeProperty
* `up` - UserProperty
* `bp` - BooleanProperty
* `ip` - IntegerProperty
* `ep` - EmailProperty
* `rp` - ReferenceProperty
* `tp` - TextProperty
* `pap` - PostalAddressProperty
* `pnp` - PhoneNumberProperty




##Views
* `sout` - self.response.out.write()
* `obj` - obj= ModelName(name="std")
* `rget` - request.get("...")
* `red` - self.redirect("...")
* `reqh` - class ReqHandlrName(webapp.RequestHandler):
* `uri` - self.request.uri
* `user` - users.get_current_user()
* `headers` - self.response.headers['Content-type']
* `render` - self.response.out.write( template.render('',{})
* `loginurl` - users.create_login_url(self.request.uri)
* `flash` - flash.msg= 'the message'



##Queries
* `.p` - put()
* `.f` - filter()
* `.fe` - fetch()
* `.o` - order()
* `.a` - all()
* `.d` - delete()
* `gq` - gql(...)


##Forms
* `form` - Form()
* `dform` - ModelForm() (django style)
