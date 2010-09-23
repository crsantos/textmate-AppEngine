#AppEngine Textmate bundle

The missing Python AppEngine Bundle, feel free to use and contribute.

##Installation

Better mixed with the [Python Django Bundle](http://svn.textmate.org/trunk/Bundles/Python%20Django.tmbundle)

	cd Library/Application\ Support/TextMate/Bundles/
	git clone git@github.com:crsantos/textmate-AppEngine.git AppEngine.tmbundle
	osascript -e 'tell app "TextMate" to reload bundles'

##Snippets

### Models
* `model` / `poly` - The standard AppEngine Models for DB.

#### Properties
* `sp` - StringProperty
* `bp` - BooleanProperty
* `blp` - BlobProperty
* `dtp` - DateProperty
* `dttp` - DateTimeProperty
* `up` - UserProperty
* `ip` - IntegerProperty
* `ep` - EmailProperty
* `rp` - ReferenceProperty
* `tp` - TextProperty
* `pap` - PostalAddressProperty
* `pnp` - PhoneNumberProperty
* `bsp` - ByteStringProperty
* `lnp` - LinkProperty
* `lp` - ListProperty
* `srp` - SelfReferenceProperty
* `blrp` - BlobReferenceProperty
* `slp` - StringListProperty
* `timep` - TimeProperty
* `imp` - IMProperty
* `geop` - GeoPtProperty
* `cp` - CategoryProperty



###Views
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
* `rit` -  run\_in_transaction(...)


###Queries
* `.p` - put()
* `.f` - filter()
* `.fe` - fetch()
* `.o` - order()
* `.a` - all()
* `.d` - delete()
* `gq` - gql(...)


###Forms
* `form` - Form()
* `dform` - ModelForm() (django style)
