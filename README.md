# video-watch
This is to make my videos work well
echo "# go-dragon-go" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Heidi999/go-dragon-go.git
git push -u origin master

/* Swift */

let options = AdColonyAppOptions()

// Indicates the GDPR requirement of the user. If it's true, the user's subject to the GDPR laws.
options.gdprRequired = true;

// Your user's consent string. In this case, the user has given consent to store and process personal information.
options.gdprConsentString = "1"; 

// Pass options object to AdColony in configure call
AdColony.configure(withAppID: /* App ID */, zoneIDs: /* Zone IDs */, options: options) { [weak self] (zones) in
   // ...
}
