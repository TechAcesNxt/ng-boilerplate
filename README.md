* angular - done
* ngrx - done
* angular material - [https://material.angular.io/](https://material.angular.io/) \- done
* nativescript - [https://play.nativescript.org/](https://play.nativescript.org/) \- done [https://www.nativescript.org/blog/how-to-build-a-pwa-an-ios-app-and-an-android-app-from-one-codebase](https://www.nativescript.org/blog/how-to-build-a-pwa-an-ios-app-and-an-android-app-from-one-codebase)
* apollo - done
* PWA - [https://web.dev/creating-pwa-with-angular-cli/](https://web.dev/creating-pwa-with-angular-cli/) [https://angular.io/guide/service-worker-intro](https://angular.io/guide/service-worker-intro) \- done
* Serverside rendering ng add @nguniversal/express-engine - done
* [https://compodoc.app/](https://compodoc.app/)
* OAuth - [https://www.npmjs.com/package/angularx-social-login](https://www.npmjs.com/package/angularx-social-login)
* [https://levelup.gitconnected.com/sign-in-with-google-oauth-in-angular-8-e716ed7f3b2f](https://levelup.gitconnected.com/sign-in-with-google-oauth-in-angular-8-e716ed7f3b2f)
* [https://auth0.com/blog/angular-2-authentication/](https://auth0.com/blog/angular-2-authentication/)

<br>
- - -

* We need to run ng add @nativescript/schematics for every new project
* ng g c new-component --module app : [https://docs.nativescript.org/angular/code-sharing/migrating-a-web-project](https://docs.nativescript.org/angular/code-sharing/migrating-a-web-project)
    * Need to modify 2 node\_modules files under C:\stacked\node\_modules\\@nativescript\angular\ to make storyboard work:
        * <span class="colour" style="color: rgb(238, 255, 255);">Renderer2</span><span class="colour" style="color: rgb(240, 113, 120);"> </span><span class="colour" style="color: rgb(137, 221, 255);">*as*</span><span class="colour" style="color: rgb(240, 113, 120);"> </span><span class="colour" style="color: rgb(238, 255, 255);">Renderer</span><span class="colour" style="color: rgb(240, 113, 120);"> </span><span class="colour" style="color: rgb(137, 221, 255);">}</span><span class="colour" style="color: rgb(238, 255, 255);"> </span><span class="colour" style="color: rgb(137, 221, 255);">*from*</span><span class="colour" style="color: rgb(238, 255, 255);"> </span><span class="colour" style="color: rgb(137, 221, 255);">"</span><span class="colour" style="color: rgb(195, 232, 141);">@angular/core</span><span class="colour" style="color: rgb(137, 221, 255);">"; in ns-router-link-active.d.ts</span>
        * <span class="colour" style="color: rgb(137, 221, 255);">*import*</span><span class="colour" style="color: rgb(238, 255, 255);"> </span><span class="colour" style="color: rgb(137, 221, 255);">{</span><span class="colour" style="color: rgb(240, 113, 120);"> </span><span class="colour" style="color: rgb(238, 255, 255);">ɵDomAdapter</span><span class="colour" style="color: rgb(240, 113, 120);"> </span><span class="colour" style="color: rgb(137, 221, 255);">}</span><span class="colour" style="color: rgb(238, 255, 255);"> </span><span class="colour" style="color: rgb(137, 221, 255);">*from*</span><span class="colour" style="color: rgb(238, 255, 255);"> </span><span class="colour" style="color: rgb(137, 221, 255);">'</span><span class="colour" style="color: rgb(195, 232, 141);">@angular/common</span><span class="colour" style="color: rgb(137, 221, 255);">'; in dom-adapter.d.ts</span>