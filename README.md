
# customs-declarations-stub

 [ ![Download](https://api.bintray.com/packages/hmrc/releases/customs-declarations-stub/images/download.svg) ](https://bintray.com/hmrc/releases/customs-declarations-stub/_latestVersion)

This application provides a stub for Customs Declarations API that enables frontend services that use Customs Declarations API with a stub to develop locally without depending on the API. 
This stub is used by customs-declare-imports-frontend.

### Usage custom notificaitons
If you send a declaration with specific letter at the beginning of the LRN you can control what notifications you receive.

If LRN starts with:
- 'G' - Stub will send Accepted notification
- 'B' - Stub will send Rejected notification
- 'D' - Stub will send Accepted and Additional Documents Required notifications
- other letters will invoke default behaviour which is Accepted notification

### License

This code is open source software licensed under the [Apache 2.0 License]("http://www.apache.org/licenses/LICENSE-2.0.html").
