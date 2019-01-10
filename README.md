# Android-links
![](https://img.shields.io/badge/Updated-January%20%207,%202019-brightgreen.svg)

Jump to
- [Android](#android)
   - [Views](#views)
   - [Context](#context)
   - [Fragment](#fragment)
   - [Service](#service)
   - [Themes](#themes)
   - [Gradle](#gradle)
   - [Architecture](#architecture)
   - [Other](#other)
 - [Programming language](#programming-language) 
   - [Kotlin](#kotlin)
   - [Java](#java)
- [Software development](#software-development)
   - [OOP](#oop)
   - [Design patterns](#patterns)
   - [Tests](#tests)
   - [Git](#git)
   - [Developer Work](#work)
   - [Developer Life](#life)
- [Libraries](#libraries)
   - [Rx](#rx)
   - [Dagger 2](#dagger)

# Android

## Views
[back to top](#readme)
* Main
    * [Greyscale Views on Android](http://blog.bradcampbell.nz/greyscale-views-on-android/)
    * [Animating Android Activities and Views with Left and Right Slide Animations](https://kylewbanks.com/blog/left-and-right-slide-animations-on-android-activity-or-view)
    * [Using Custom Views As Menu Items](http://blog.stablekernel.com/using-custom-views-as-menu-items)
    * [ConstraintLayout - Guidelines, Barriers, Chains and Groups](https://riggaroo.co.za/constraintlayout-guidelines-barriers-chains-groups/)
    * [Playing with elevation in Android](https://blog.usejournal.com/playing-with-elevation-in-android-91af4f3be596)
    * [An Android Toolbar and Action Bar Color Guide](https://www.codeandkits.com/Blog/2018/03/26/an-android-toolbar-and-action-bar-color-guide/)
    * [Drawing multiline text to Canvas](https://medium.com/over-engineering/drawing-multiline-text-to-canvas-on-android-9b98f0bfa16a)
    * [Spantastic text styling with Spans](https://medium.com/google-developers/spantastic-text-styling-with-spans-17b0c16b4568)
    * [Customizing Switch using XML](https://medium.com/@elye.project/customizing-switch-using-xml-ca0d37204a86)
    * [[Youtube] View only Android apps at scale](https://www.youtube.com/watch?v=kAAnIN-IqWw)
    * [Rich text battle: TextView vs WebView](http://www.hidroh.com/2016/02/27/richtext-textview-versus-webview/)
    * [A guide for Android ImageView ScaleType and adjustViewBounds](https://proandroiddev.com/a-guide-for-android-imageview-scaletype-and-adjustviewbounds-64a1e4a35503)
    * [ViewPager without fragments](https://www.bignerdranch.com/blog/viewpager-without-fragments/)
    * [Introduction to SpringAnimation with examples](https://www.thedroidsonroids.com/blog/android/springanimation-examples/)
    * [-nodpi, -anydpi, and WTF?](https://commonsware.com/blog/2015/12/21/nodpi-anydpi-wtf.html)
    * [TransitionDrawable — Small Gems of the Android Framework](https://proandroiddev.com/transitiondrawable-small-gems-of-the-android-framework-4dcdd3c83319)
    * [Preferred way to set clickable image icon](https://medium.com/@elye.project/preferred-way-to-set-clickable-image-icon-95b0c88f3cd9)
    * [Selectively Locking An Android UI](https://mpope9.github.io/2018/09/06/LockingAndroidUI.html)
    * [[Yotube] Loving Lean Layouts](https://www.youtube.com/watch?v=-xAdDqwaWJk)
* RecyclerView
    * [How to filter a RecyclerView with a SearchView](https://www.codementor.io/tips/1237823034/how-to-filter-a-recyclerview-with-a-searchview)
    * [Implementing a modal selection helper for RecyclerView](https://medium.com/@BladeCoder/implementing-a-modal-selection-helper-for-recyclerview-1e888b4cd5b9)
    * [RecyclerView animations done right](http://frogermcs.github.io/instamaterial-recyclerview-animations-done-right/)
    * [Your ViewHolders are Dumb. Make ’em Not Dumb](https://jonfhancock.com/your-viewholders-are-dumb-make-em-not-dumb-82e6f73f630c)
    * [ItemDecoration in Android](https://medium.com/proandroiddev/itemdecoration-in-android-e18a0692d848)
    * [[Yotube] Mastering RecyclerView Layouts](https://www.youtube.com/watch?v=gs_C1E8HwvE)
    * [RecyclerView — More Animations with Less Code using Support Library ListAdapter](https://medium.com/@trionkidnapper/recyclerview-more-animations-with-less-code-using-support-library-listadapter-62e65126acdb)
    * [Right way of setting margin on Recycler View’s cell](https://medium.com/@elye.project/right-way-of-setting-margin-on-recycler-views-cell-319da259b641)
* WebView
    * [Android WebView — Downloading Images](https://medium.com/@trionkidnapper/android-webview-downloading-images-f0ec21ac75d2)
    * [Android WebViews: All about security](https://proandroiddev.com/android-webviews-1cbe1ffb7a2b)
    * [Managing Keyboard on Webview](https://medium.com/@elye.project/managing-keyboard-on-webview-d2e89109d106)    

---

## Context
[back to top](#readme)
* [Context, What Context?](https://possiblemobile.com/2013/06/context/)
* [Which Context should I use in Android?](https://medium.com/@ali.muzaffar/which-context-should-i-use-in-android-e3133d00772c)
* [Why Having Global Static References to Application Contexts is Probably not the Best Idea](https://www.philosophicalhacker.com/2015/07/14/why-static-references-to-application-contexts-are-probably-not-the-best-idea/)
* [Android Context Needs Isolation](https://www.techyourchance.com/android-context-needs-isolation)
* [Mastering Android context](https://medium.freecodecamp.org/mastering-android-context-7055c8478a22)

---

## Fragment
[back to top](#readme) 
* [Advocating Against Android Fragments](https://corner.squareup.com/2014/10/advocating-against-android-fragments.html)
* [Fragment Transactions & Activity State Loss](http://www.androiddesignpatterns.com/2013/08/fragment-transaction-commit-state-loss.html)
* [The Dark side of Fragments](https://android.jlelse.eu/the-dark-side-of-fragments-ca0f871b1199)
* [Android Fragment Lifecycle for Professional Developers](https://www.techyourchance.com/android-fragment-lifecycle-for-professional-developers/)
* [Lifecycle & Fragments backstack](https://medium.com/citerus/lifecycle-fragments-backstack-f32e34f012d5)
* [[Youtube] Life Without Fragments](https://www.youtube.com/watch?v=jl1HRiCaAP4)
* [From Fragments to Activity: the Lambda Way](https://medium.com/groupon-eng/from-fragments-to-activity-the-lambda-way-32c768c72aa9)

---

## Service
[back to top](#readme)
 * [How to handle background services in Android O](https://medium.com/@kevalpatel2106/how-to-handle-background-services-in-android-o-f96783e65268)
* [Exploring Background Execution Limits on Android Oreo](https://medium.com/exploring-android/exploring-background-execution-limits-on-android-oreo-ab384762a66c)
* [Services. The life with/without. And WorkManager](https://medium.com/google-developer-experts/services-the-life-with-without-and-worker-6933111d62a6)

---

## Themes
[back to top](#readme)
* [How to style AlertDialogs like a pro](http://blog.supenta.com/2014/07/02/how-to-style-alertdialogs-like-a-pro/)
* [Android Themes & styles, a real architecture](http://blog.octo.com/en/android-themes-styles-a-real-architecture/)
* [Android Resources Refactoring](https://news.realm.io/news/android-resources-refactoring/)
* [Styling Colors & Drawables, Theme Attributes](https://www.androiddesignpatterns.com/2016/08/contextcompat-getcolor-getdrawable.html)
* [Polishing UI: Android StateListAnimator](https://android.jlelse.eu/polishing-ui-android-statelistanimator-7b74a06b85a5)
* [[Yotube] Using Styles and Themes Without Going Crazy](https://www.youtube.com/watch?v=Jr8hJdVGHAk)

---

## Gradle
[back to top](#readme)
* [10 Tips to Improve Your Gradle Build Time](http://www.universalmind.com/blog/10-tips-to-improve-your-gradle-build-time/)
* [A strategy to secure your API keys using Gradle](https://medium.com/@cassioso/a-strategy-to-secure-your-api-keys-using-gradle-b9c107272860)
* [[Yotube] Speeding Up Your Android Gradle Builds](https://www.youtube.com/watch?v=7ll-rkLCtyk)
* [How to speed up your slow Gradle builds](https://android.jlelse.eu/how-to-speed-up-your-slow-gradle-builds-5d9a9545f91a)
* [Renaming Your Gradle Build Files](http://www.developerphil.com/renaming-your-gradle-build-files/)
* [[Yotube] Gradle: From User to Addict](https://www.youtube.com/watch?v=-C7TtnPJ7ms)
* [Experimenting with Gradle dependencies](http://alexfu.github.io/android/2017/11/07/experimenting-with-gradle-dependencies.html)

---

## Architecture
[back to top](#readme)
* MVP
    * [Android MVP: Keeping Presenters Alive](https://medium.com/@trionkidnapper/android-mvp-keeping-presenters-alive-a91b9e080761)
    * [Presenters don't need lifecycle events](http://hannesdorfmann.com/android/presenters-dont-need-lifecycle)
    * [Presenters are not for persisting](https://hackernoon.com/presenters-are-not-for-persisting-f537a2cc7962)
    * [Where to Unbind the Presenter](https://proandroiddev.com/where-to-unbind-the-presenter-e50ce343d4ce)
    * [Restoring State in Android MVP Architecture](https://pspdfkit.com/blog/2016/restoring-state-in-android-mvp-architecture/)
* Architecture Components
    * [Android Architecture Components](https://proandroiddev.com/android-architecture-components-cb1ea88d3835)
    * [Introduction to Android Architecture Components](https://code.tutsplus.com/tutorials/introduction-to-android-architecture--cms-28749)
    * [Architecture Components - I'm not a purist but](http://hannesdorfmann.com/android/arch-components-purist)
    * [Background and Foreground events with Android Architecture Components](https://medium.com/@arturogdg/background-and-foreground-events-with-android-architecture-components-233fdd9fa855)
    * [Android ViewModel should be called scopedComponent](https://medium.com/@mattcarroll/android-viewmodel-should-be-called-scopedcomponent-ffcafdbd7a98)
    * [[Video] Clean App Design with Architecture Components](https://academy.realm.io/posts/360-andev-2017-chuck-greb-clean-app-design-architecture-components/)
    * [ViewModels: Persistence, onSaveInstanceState(), Restoring UI State and Loaders](https://medium.com/google-developers/viewmodels-persistence-onsaveinstancestate-restoring-ui-state-and-loaders-fc7cc4a6c090)
    * [Concise Error Handling with LiveData and Retrofit](https://proandroiddev.com/concise-error-handling-with-livedata-and-retrofit-15937ceb555b)
* Other    
    * [Weighing in on the Holy Architecture War](https://medium.com/@yonatanvlevin/weighing-in-on-the-holy-architecture-war-my-take-on-architecture-components-31f7025e9c66)
    * [Android Architecture(MVC, MVP, MVVM)](https://android.jlelse.eu/android-architecture-2f12e1c7d4db)
    * [Android Architecture Patterns Part 1: Model-View-Controller](https://medium.com/upday-devs/android-architecture-patterns-part-1-model-view-controller-3baecef5f2b6)
    * [Architectures of Android applications](https://medium.com/@bvmaks/architectures-of-android-applications-244a083bf132)
    * [Cargo Cult MVVM => The death knell of WPF](http://cargocultsoftwaredevelopment.blogspot.com/2010/10/cargo-cult-mvvm-death-knell-of-wpf.html)
    * [MVP to MVVM transformation](https://proandroiddev.com/mvp-to-mvvm-transformation-611959d5e0ca)
    * [[Youtube] Android Software Architecture by Example](https://www.youtube.com/watch?v=7t7MN8e1W7s)
    * [[Youtube] Half Way to clean architecture](https://www.youtube.com/watch?v=R89ufpJI3SY)
    * [[Youtube] Application Architecture: Designing Offline Application Case Studies](https://www.youtube.com/watch?v=n8nG5K_3BJM)

---

## Other
[back to top](#readme)
* Main
    * [Identifying an Android Device](http://handstandsam.com/2017/05/04/identifying-an-android-device/)
    * [Streamlining eero’s Android build process](https://medium.com/@jordanjoz/streamlining-eeros-android-build-process-6a870ef40a89#.svunhmwgi)
    * [Glide vs Picasso](https://medium.com/@multidots/glide-vs-picasso-930eed42b81d)
    * [An introduction to Android Instant Apps](https://willowtreeapps.com/ideas/an-introduction-to-android-instant-apps)
    * [Live Template for RecyclerView Adapter in Android Studio](https://tech.fleka.me/live-template-for-recyclerview-adapter-in-android-studio-5a4e7342bffc)
    * [Android Task and Back Stack Review](https://blog.mindorks.com/android-task-and-back-stack-review-5017f2c18196)
    * [Going multiprocess on Android](https://medium.com/@rotxed/going-multiprocess-on-android-52975ed8863c)
    * [Exploring the Android EmojiCompat Library](https://medium.com/exploring-android/exploring-the-android-emoji-compatibility-library-1b9f3bb724aa)
    * [Optimizing the Performance of Vector Drawables](https://medium.com/upday-devs/optimizing-the-performance-of-vector-drawables-680a4c456286)
    * [A Curious Case of Multiple Locales](https://blog.egorand.me/a-curious-case-of-multiple-locales/)
    * [Task Stack](https://blog.stylingandroid.com/task-stack/)
    * [Exploring Android P: Fingerprint Dialog](https://medium.com/exploring-android/exploring-android-p-fingerprint-dialog-fa672ae62c6f)
    * [Understanding Activity.runOnUiThread()](https://medium.com/@yossisegev/understanding-activity-runonuithread-e102d388fe93)
    * [Add Logs Without Using Code](https://android.jlelse.eu/add-logs-without-using-code-bd49fe9202ca)
    * [Safe-Integration of Realm in Android production code](https://medium.com/@Viraj.Tank/realm-integration-in-android-best-practices-449919d25f2f)
    * [How to Correctly Store App-Specific Files in Android](https://www.grokkingandroid.com/how-to-correctly-store-app-specific-files-in-android/)
    * [Android APK signature scheme v3](https://www.guardsquare.com/en/blog/android-apk-signature-scheme-v3-context-and-new-opportunities)
    * [Sharing Content between Android apps](https://medium.com/androiddevelopers/sharing-content-between-android-apps-2e6db9d1368b)
    * [Exploring the Android App Bundle](https://medium.com/google-developer-experts/exploring-the-android-app-bundle-ca16846fa3d7)
    * [[Yotube] Timing is Everything: How to use Timer, Handler, and AlarmManager](https://www.youtube.com/watch?v=CzNFjCQhCV0)
    * [[Yotube] Linty Fresh](https://www.youtube.com/watch?v=YseGWp7iouM)
    * [[Yotube] Requesting Permissions at Run Time](https://www.youtube.com/watch?v=WGz-alwVh8A)
    * [[Yotube] How the Main Thread works](https://www.youtube.com/watch?v=eAtMon8ndfk)
    * [[Yotube] Exploring Custom Activity Transitions](https://www.youtube.com/watch?v=HLhA0I00TnI)
    * [[Yotube] Tools of the Trade](https://www.youtube.com/watch?v=AeoeD7K8vKI)
    * [[Video] Exploring the Activity Lifecycle](https://realm.io/news/activities-in-the-wild-exploring-the-activity-lifecycle-android/)
* Net
    * [Advanced Retrofit](https://academy.realm.io/posts/advanced-retrofit-mobilization-2017/)
    * [Configuring Retrofit 2 Client in Android](https://proandroiddev.com/configuring-retrofit-2-client-in-android-130455eaccbd)
    * [Various methods to debug HTTP traffic in Android applications](https://proandroiddev.com/various-methods-to-debug-http-traffic-in-the-android-application-8685b9183418)
* ProGuard
    * [Practical ProGuard rules examples](https://medium.com/google-developers/practical-proguard-rules-examples-5640a3907dc9)
    * [Troubleshooting ProGuard issues on Android](https://medium.com/androiddevelopers/troubleshooting-proguard-issues-on-android-bce9de4f8a74)
    * [[Yotube] Bulletproof Android](https://www.youtube.com/watch?v=1yF5sqGJo90)
* Multidex
    * [65K methods](https://medium.com/@rotxed/dex-skys-the-limit-no-65k-methods-is-28e6cb40cf71)
    * [Use the Android apk analyzer to reduce your apk size](https://riggaroo.co.za/use-android-apk-analyzer-reduce-apk-size/)
    * [Comparing APK sizes](https://android.jlelse.eu/comparing-apk-sizes-a0eb37bb36f)
    * [[Yotube] Understanding and Experimenting with MultiDex](https://www.youtube.com/watch?v=skmOBriQ28E)
* Memory leak
    * [What you need to know about Android app memory leaks](https://techbeacon.com/what-you-need-know-about-android-app-memory-leaks)
    * [Android leak pattern: subscriptions in views](https://medium.com/square-corner-blog/android-leak-pattern-subscriptions-in-views-18f0860aa74c)
    * [Our battle with the OutOfMemory army](https://medium.com/lalafo-engineering/our-battle-with-the-outofmemory-army-bd6b384f1f0c)

---

# Programming language

## Kotlin
[back to top](#readme)
* Data Classes
    * [Creating multiple constructors for Data classes in Kotlin](https://medium.com/proandroiddev/creating-multiple-constructors-for-data-classes-in-kotlin-32ad27e58cac)
    * [Representing View State with Kotlin Data Classes](https://medium.com/@trionkidnapper/viewmodel-and-kotlin-data-class-7d3a3b854805)
    * [Data Classes are The Best Kotlin Feature](https://www.techyourchance.com/data-classes-best-kotlin-feature/)
    * [Kotlin data classes and sensitive information](https://mustafaali.net/2018/01/14/Kotlin-data-classes-and-sensitive-information/)
* Sealed Classes
    * [Modeling ViewModel States Using Kotlin’s Sealed Classes](https://engineering.udacity.com/modeling-viewmodel-states-using-kotlins-sealed-classes-a5d415ed87a7)
    * [Simplify your Android code by delegating to sealed classes](https://medium.com/halcyon-mobile/simplify-your-android-code-by-delegating-to-sealed-classes-99304c509321)
    * [Handaling optionals errors using kotlin sealed classes](https://articles.caster.io/android/handling-optional-errors-using-kotlin-sealed-classes/)
    * [Kotlin Sealed Classes — enums with swag](https://proandroiddev.com/kotlin-sealed-classes-enums-with-swag-d3c4b799bcd4)
* Delegates
    * [Kotlin is Dope And So Are Its Custom Property Delegates](https://robots.thoughtbot.com/kotlin-is-dope-and-so-are-its-custom-property-delegates)
    * [Kotlin — Faster Lazy for Android](https://proandroiddev.com/kotlin-faster-lazy-for-android-7328ec8d8d57)
    * [The magic in Kotlin: Delegates](https://proandroiddev.com/the-magic-in-kotlin-delegates-377d27a7b531)
    * [Kotlin delegates in Android development](https://proandroiddev.com/kotlin-delegates-in-android-development-part-2-2c15c11ff438)
* Type System
    * [Kotlin Type Hierarchy](http://natpryce.com/articles/000818.html)
    * [Nothing (else) matters in Kotlin](https://proandroiddev.com/nothing-else-matters-in-kotlin-994a9ef106fc)
    * [Kotlin’s ‘Nothing’ Type](https://proandroiddev.com/kotlins-nothing-type-946de7d464fb)    
    * [The Ins and Outs of Generic Variance in Kotlin](https://typealias.com/guides/ins-and-outs-of-generic-variance/)    
    * [Kotlin — Mastering generics nullability](https://medium.com/@igorwojda/kotlin-deep-dive-into-generics-nullability-9853d9a9f50d)   
    * [All About Type Aliases in Kotlin](https://typealias.com/guides/all-about-type-aliases/)
    * [An Illustrated Guide to Covariance and Contravariance in Kotlin](https://typealias.com/guides/illustrated-guide-covariance-contravariance/)
* Properties
    * [Inlining Kotlin Properties](https://blog.egorand.me/inlining-kotlin-properties/amp/)
    * [Safely accessing lateinit properties in Kotlin](https://upcurve.engineering/accessing-lateinit-kotlin/)
    * [Kotlin and Android #2 — Treacherous properties](https://tips.seebrock3r.me/kotlin-and-android-2-treacherous-properties-562966242c2d)
    * [Kotlin: should I define Function or Property?](https://blog.kotlin-academy.com/kotlin-should-i-define-function-or-property-6786951da909)
* Android
    * [How kotlin became our primary language for android](https://medium.com/uptech-team/how-kotlin-became-our-primary-language-for-android-3af7fd6a994c#.hj4k8m25l)  
    * [Starting Activities with Kotlin](https://medium.com/@passsy/starting-activities-with-kotlin-my-journey-8b7307f1e460)
    * [Kotlin + buildSrc for Better Gradle Dependency Management](https://handstandsam.com/2018/02/11/kotlin-buildsrc-for-better-gradle-dependency-management/)
    * [The danger of assumptions: Kotlin with Android custom views](https://blog.q42.nl/the-danger-of-assumptions-kotlin-with-android-custom-views-adb79bf2da45)
    * [Improving findViewById with Kotlin](https://medium.com/@quiro91/improving-findviewbyid-with-kotlin-4cf2f8f779bb)
    * [A Better Way to Launch Activities on Android](https://medium.com/capital-one-developers/a-better-way-to-launch-activities-on-android-8a1045181b16)
    * [Hacking Architecture Components by using Kotlin](https://antonioleiva.com/architecture-components-kotlin/)   
    * [[Video] Advancing Android Development with Kotlin](https://realm.io/news/oredev-jake-wharton-kotlin-advancing-android-dev/)
    * [Custom attributes using BindingAdapters in Kotlin](https://proandroiddev.com/custom-attributes-using-bindingadapters-in-kotlin-971ef8fcc259)
    * [Kotlin Android Extensions: Using View Binding the right way](https://proandroiddev.com/kotlin-android-extensions-using-view-binding-the-right-way-707cd0c9e648)
    * [Making the Android Studio Layout Editor Better With Kotlin](https://blog.shazam.com/making-the-android-studio-layout-editor-better-with-kotlin-997ca0653923)
* Coroutines
    * [[Youtube] Asynchronous Programming with Kotlin](https://www.youtube.com/watch?v=krfGMLuhB8M)
    * [Diving deep into Kotlin Coroutines](https://www.kotlindevelopment.com/deep-dive-coroutines/)
    * [Simple asynchronous loading with Kotlin Coroutines](https://hellsoft.se/simple-asynchronous-loading-with-kotlin-coroutines-f26408f97f46)
* Functional Programming
    * [Function references in Kotlin](https://antonioleiva.com/function-references-kotlin/)
    * [Listeners with several functions in Kotlin](https://antonioleiva.com/listeners-several-functions-kotlin/)
    * [Comping with kotlin's scope functions](https://kotlinexpertise.com/coping-with-kotlins-scope-functions/)
    * [the tldr; on Kotlin’s let, apply, also, with and run functions](https://proandroiddev.com/the-tldr-on-kotlins-let-apply-also-with-and-run-functions-6253f06d152b)
    * [Kotlin Functional Programming: Does it make sense?](https://medium.com/@JorgeCastilloPr/kotlin-functional-programming-does-it-make-sense-36ad07e6bacf)
    * [Lambda Expressions in Kotlin](http://www.baeldung.com/kotlin-lambda-expressions)
* Extension Functions
    * [How to Abuse Kotlin Extension Functions](https://www.philosophicalhacker.com/post/how-to-abuse-kotlin-extension-functions/)
    * [Getting rid of boilerplate with Kotlin Android Extensions](https://www.kotlindevelopment.com/kotlin_android_extensions_eliminate_findviewbyid/)    
* Patterns
    * [Gang of Four Patterns in Kotlin](https://dev.to/lovis/gang-of-four-patterns-in-kotlin)
    * [Kotlin tips: Singleton, Utility Functions, group Object Initialization](https://medium.com/default-to-open/kotlin-tips-singleton-utility-functions-group-object-initialization-and-more-27cdd6f63a41)   
    * [How “Effective Java” may have influenced the design of Kotlin](http://www.lukle.at/blog/2017/08/how-effective-java-may-have-influenced-the-design-of-kotlin%E2%80%8A-%E2%80%8Apart-3/)
    * [DI for lazy kotliniers](https://jankotlin.wordpress.com/2017/09/18/di-for-lazy-kotliniers/)
    * [Effective Kotlin: Use Sequence for bigger collections with more than one processing step](https://blog.kotlin-academy.com/effective-kotlin-use-sequence-for-bigger-collections-with-more-than-one-processing-step-649a15bb4bf)
    * [Default implementations for interfaces](https://medium.com/a-problem-like-maria/default-implementations-for-interfaces-afd0b9316a8a)    
* Variable
    * [Where Should I Keep My Constants in Kotlin?](https://blog.egorand.me/where-do-i-put-my-constants-in-kotlin/)  
    * [A few facts about Companion objects](https://blog.kotlin-academy.com/a-few-facts-about-companion-objects-37e18429b725)
    * [You don't need a variable for this](https://forcelain.github.io/2017/08/04/you-don-t-need-a-variable-for-this.html)
    * [A practical explanation for initialization modifiers in Kotlin](https://medium.com/google-developer-experts/a-practical-explanation-for-initialization-modifiers-in-kotlin-9f52096ff1ca)
    * [Kotlin variable, to be Lazy, or to be Late?](https://medium.com/@elye.project/kotlin-variable-to-be-lazy-or-to-be-late-ab865c682d61) 
* Other
    * [10 Reasons Why You Should Drop Java and Switch to Kotlin](https://moducode.com/blog/10-reasons-java-vs-kotlin/)
    * [How to remove all !! from your Kotlin code](https://android.jlelse.eu/how-to-remove-all-from-your-kotlin-code-87dc2c9767fb)
    * [Anko for developer](https://www.kotlindevelopment.com/why-should-use-anko/)
    * [Learning Kotlin by Mistake](https://engineering.udacity.com/learning-kotlin-by-mistake-b99304b7d724)
    * [Simplified code with kotlin](https://android.jlelse.eu/simplified-code-with-kotlin-cda9915c9fb9)
    * [Preconditions.kt: Validate Your Kotlin](https://blog.egorand.me/preconditions-kt-validate-your-kotlin/)
    * [Safe, concise text parsing with regex destructuring in Kotlin](https://medium.com/@garnop/safe-concise-text-parsing-with-regex-destructuring-in-kotlin-b8f77ef1e30c)
    * [A life without ifs](https://medium.com/a-problem-like-maria/a-life-without-ifs-e44967e5c77b)
    * [Kotlin + Dagger 2 Gotchas](https://medium.com/@vlazzle/kotlin-dagger-2-gotchas-ebb6bb2ac506)
    * [Demystifying the inline keyword](https://www.kotlindevelopment.com/inline-noinline-crossinline-reified/)
    * [Annotations for your Java-friendly Kotlin code](https://proandroiddev.com/annotations-for-your-java-friendly-kotlin-code-badfbedec14)
    * [Looping in Kotlin](https://medium.com/@elye.project/looping-in-kotlin-65b54d05ad21)
    * [[Youtube] Kotlin in Production](https://www.youtube.com/watch?v=mDpnc45WwlI)
    * [What is “concurrent” access to mutable state?](https://proandroiddev.com/what-is-concurrent-access-to-mutable-state-f386e5cb8292)
    * [API Design — Handling exceptions](https://medium.com/@ZakTaccardi/api-design-handling-exceptions-84a143e32232)
    
---

## Java
[back to top](#readme)
* [Understanding how references work in android and java](https://medium.com/google-developer-experts/finally-understanding-how-references-work-in-android-and-java-26a0d9c92f83)
* [On properly using volatile and synchronized](https://medium.com/google-developer-experts/on-properly-using-volatile-and-synchronized-702fc05faac2)
* [Default methods + lambdas = less code](https://android.jlelse.eu/default-methods-lambdas-less-code-aa0e63d6c5d9)

---

# Software development

## OOP
[back to top](#readme)
* [Typical Mistakes in Java Code](https://www.yegor256.com/2014/04/27/typical-mistakes-in-java-code.html)
* [Objects vs. Data Structures](https://hackernoon.com/objects-vs-data-structures-e380b962c1d2)
* [OOP Alternative to Utility Classes](https://www.yegor256.com/2014/05/05/oop-alternative-to-utility-classes.html)
* [Why extends is evil](https://www.javaworld.com/article/2073649/core-java/why-extends-is-evil.html)
* [Why null is Bad?](https://www.yegor256.com/2014/05/13/why-null-is-bad.html)
* [Static methods violate Dependency Inversion principle](https://www.vzurauskas.com/2018/09/09/static-methods-violate-dependency-inversion-principle/)
* [Objects Should Be Immutable](https://www.yegor256.com/2014/06/09/objects-should-be-immutable.html)
* [Solid Is OOP for Dummies](https://www.yegor256.com/2017/03/28/solid.html)
* [Getters/Setters. Evil. Period.](https://www.yegor256.com/2014/09/16/getters-and-setters-are-evil.html)
* [Seven Virtues of a Good Object](https://www.yegor256.com/2014/11/20/seven-virtues-of-good-object.html)
* [How Immutability Helps](https://www.yegor256.com/2014/11/07/how-immutability-helps.html)
* [How Does Inversion of Control Really Work?](https://www.yegor256.com/2017/05/10/inversion-of-control.html)
* [Object Behavior Must Not Be Configurable](https://www.yegor256.com/2016/04/19/object-must-not-be-configurable.html)
* [Why Many Return Statements Are a Bad Idea in OOP](https://www.yegor256.com/2015/08/18/multiple-return-statements-in-oop.html)
* [There Can Be Only One Primary Constructor](https://www.yegor256.com/2015/05/28/one-primary-constructor.html)
* [Immutable Objects Are Not Dumb](https://www.yegor256.com/2014/12/22/immutable-objects-not-dumb.html)
* [Constructors Must Be Code-Free](https://www.yegor256.com/2015/05/07/ctors-must-be-code-free.html)
* [Class Casting Is a Discriminating Anti-Pattern](https://www.yegor256.com/2015/04/02/class-casting-is-anti-pattern.html)

---

## Patterns
[back to top](#readme) 
* [The Evolution Of The Repository Pattern - Be Aware Of Over Abstraction](http://hannesdorfmann.com/android/evolution-of-the-repository-pattern)
* [Common Design Patterns for Android](https://www.raywenderlich.com/109843/common-design-patterns-for-android)
* [Designing something solid](https://www.novoda.com/blog/designing-something-solid/)
* [Writing Better Adapters](https://proandroiddev.com/writing-better-adapters-1b09758407d2)
* [Don’t use DAO, use Repository](https://thinkinginobjects.com/2012/08/26/dont-use-dao-use-repository/)
* [Design Patterns in Android – Observer](https://www.thedroidsonroids.com/blog/design-patterns-android-observer-2)
* [Singletons The Safe Way](https://medium.com/@mattcarroll/singletons-the-safe-way-9d1e019220fc)
* [Android Chain Gangs](https://medium.com/@mattcarroll/android-chain-gangs-f35419f5f3dd)
* [Defensive Programming via Validating Decorators](https://www.yegor256.com/2016/01/26/defensive-programming.html)
* [Vertical and Horizontal Decorating](https://www.yegor256.com/2015/10/01/vertical-horizontal-decorating.html)
* [Great Adpater Hell Escape](http://hannesdorfmann.com/android/adapter-delegates)
* [Building vertical decorators right](https://www.vzurauskas.com/2018/10/28/building-vertical-decorators-right/)
* [In-app navigation wih coordinators](http://hannesdorfmann.com/android/coordinators-android)
* [Inversion of control containers and the dependency injection pattern](https://martinfowler.com/articles/injection.html)
* [Service locator vs dependency injection](http://guy-murphy.github.io/2014/11/24/service-locator-vs-dependency-injection/)

---

## Tests
[back to top](#readme)
* Main
    * [Different ways of testing exceptions in Java and JUnit](https://blog.goyello.com/2015/10/01/different-ways-of-testing-exceptions-in-java-and-junit/)
    * [Should we use mocking libraries for go testing?](https://www.philosophicalhacker.com/2016/01/13/should-we-use-mocking-libraries-for-go-testing/)
    * [Clean tests: Naming](https://android.jlelse.eu/clean-tests-part-1-naming-cce94edf0522)
    * [Clean tests: Comments](https://android.jlelse.eu/clean-tests-part-2-comments-4016ee82f186)
    * [Testing state vs. testing interaction](https://medium.com/android-testing-daily/testing-state-vs-testing-interaction-c5d7fe0bf247)
    * [Test doubles](https://medium.com/android-testing-daily/test-doubles-9a63dfaeb28b)
    * [One weird trick to name your tests](https://medium.com/@anupcowkur/one-weird-trick-to-name-your-tests-28ca1f8131c2)
    * [An Introduction to Testing Custom Views on Android](https://proandroiddev.com/an-introduction-to-testing-custom-views-on-android-10a6152f379?__s=7obepfpkzmezdyhskkzf)
    * [Myths about Unit Tests](https://8thlight.com/blog/fabien-townsend/2017/09/19/myths-about-unit-tests.html)
    * [Three Reasons Why We Should Not Use Inheritance In Our Tests](https://www.petrikainulainen.net/programming/unit-testing/3-reasons-why-we-should-not-use-inheritance-in-our-tests/)
* Android
    * [Fast and reliable UI tests on Android](https://labs.ribot.co.uk/fast-and-reliable-ui-tests-on-android-17c261b8220c#.1bilhu4hg)
    * [Espresso Test for Intent](http://pengj.me/android/test/2015/10/17/expresso-test-intent.html)
    * [How to be a mock star](https://medium.com/fueled-android/how-to-be-a-mock-star-fc00714d8c2f)
    * [Android testing: Unit testing (Part 1)](http://alexzh.com/tutorials/android-testing-unit-testing/)
    * [Android testing: Mockito and Robolectric (Part 2)](http://alexzh.com/tutorials/android-testing-mockito-robolectric/)
    * [Android testing: Espresso (Part 3)](http://alexzh.com/tutorials/android-testing-espresso-part-3/)
    * [Android testing: UI Automator (Part 4)](http://alexzh.com/tutorials/android-testing-ui-automator-part-4/)
    * [Dont Use Espresso Idling Resources like Google does](https://www.philosophicalhacker.com/post/psa-dont-use-esprsso-idling-resources-like-this/)
    * [How "Android Test Recorder" generate delays between actions](http://droidtestlab.com/delay.html)
    * [Simple way to test asynchronous actions in Android](https://medium.com/@v.danylo/simple-way-to-test-asynchronous-actions-in-android-service-asynctask-thread-rxjava-etc-d43b0402e005)
    * [Dagger 2 Testing](http://endlesswhileloop.com/blog/2016/06/23/dagger-2-testing/)
    * [Why I Don't use Robolectric](https://www.philosophicalhacker.com/post/why-i-dont-use-roboletric/)
    * [Junit testing and Android dependencies](https://android.jlelse.eu/junit-testing-and-android-dependencies-e65e66afce61)
    * [Unit testing protected lifecycle methods](https://medium.com/google-developer-experts/unit-testing-activity-lifecycle-4e740f71e68a)
    * [Unit Testable RecyclerViews](https://www.philosophicalhacker.com/post/unit-testable-recycler-views/)
    * [The 3 tiers of the Android test pyramid](https://medium.com/android-testing-daily/the-3-tiers-of-the-android-test-pyramid-c1211b359acd)
    * [Testing Views in Isolation at RoMOBOS](https://proandroiddev.com/testing-views-in-isolation-at-romobos-d288e76fe10e)
    * [Espresso Test Addiction: An Anti-pattern](https://www.philosophicalhacker.com/post/espresso-test-addiction/)
    * [Don’t Keep Activities alone is not enough for testing!](https://medium.com/@elye.project/dont-keep-activities-alone-is-not-enough-for-testing-407b7c01bd60)    

---

## Git
[back to top](#readme)
* [Keep a readable Git history](https://fangpenlin.com/posts/2013/09/30/keep-a-readable-git-history/)
* [Four Steps To Maintaining a Clean Git History](https://spin.atomicobject.com/2017/04/23/maintain-clean-git-history/)
* [Android Studio and Git Branches – How to Simplify Your Work](https://www.thedroidsonroids.com/blog/android-studio-and-git-branches-how-to-simplify-you-work)

---

## Work
[back to top](#readme)
* [Things You Should Never Do, Part I](http://www.joelonsoftware.com/articles/fog0000000069.html)
* [Code Reviews Q&A](https://blog.babylonhealth.com/code-reviews-q-a-f33c72d3b2c3)
* [Perfect code is an illusion](https://8thlight.com/blog/daniel-irvine/2016/11/11/perfect-code-is-an-illusion.html)
* [The problematic pull request](https://8thlight.com/blog/daniel-irvine/2016/11/18/the-problematic-pull-request.html)
* [Rebuild or Report?](https://blog.photoeditorsdk.com/rebuild-or-report-211d6ac6e787)
* [Flexibility Equates to Lower Quality](https://www.yegor256.com/2017/04/11/flexibility-equates-lower-quality.html)
* [Three Things I Expect From a Software Architect](https://www.yegor256.com/2015/05/11/software-architect-responsibilities.html)
* [Two Instruments of a Software Architect](https://www.yegor256.com/2015/05/13/two-instruments-of-software-architect.html)
* [The Churn](http://blog.cleancoder.com/uncle-bob/2016/07/27/TheChurn.html)
* [Feature Flags in Native Mobile Development are a Must](https://www.techyourchance.com/feature-flags-in-native-mobile-development-are-must/)
* [Keep Your Features in Progress Out of Your Release Builds](http://antoine-merle.com/blog/2015/10/10/keep-your-features-in-progress-out-of-your-release-builds/)
* [Scrum and Kanban – Are They That Different After All?](https://perfectial.com/blog/scrum-and-kanban-are-they-that-different-after-all/)
* [What's the Difference? Agile vs Scrum vs Waterfall vs Kanban](https://www.smartsheet.com/agile-vs-scrum-vs-waterfall-vs-kanban)

---

## Life
[back to top](#readme)
* [40 Hours is enough](https://hackernoon.com/40-hours-is-enough-86d7166911ea)
* [Programmer 60-80 hour weeks](http://brianknapp.me/programmer-60-80-hour-weeks/)
* [The egoless programmer](https://8thlight.com/blog/daniel-irvine/2016/09/30/the-egoless-programmer.html)
* [“Eat, sleep, code, repeat” is such bullshit](https://m.signalvnoise.com/eat-sleep-code-repeat-is-such-bullshit-c2a4d9beaaf5)
* [Is group chat making you sweat?](https://m.signalvnoise.com/is-group-chat-making-you-sweat-744659addf7d)
* [Professional Developer: What Does It Mean?](https://www.thedroidsonroids.com/blog/professional-developer-what-does-it-mean)
* [I Don’t Have Time is a Myth](http://www.donnfelker.com/i-dont-have-time-is-a-myth/?utm_source=androiddevdigest)
* [I "Love" Anti-patterns](https://dev.to/levimoreira/i-love-anti-patterns-1bj1)
* [Soft Skills Demystified](https://www.yegor256.com/2018/08/29/soft-skills.html)
* [How to Be a Good Office Slave](https://www.yegor256.com/2015/10/06/how-to-be-good-office-slave.html)
* [How to Pay Programmers Less](https://www.yegor256.com/2016/12/06/how-to-pay-programmers-less.html)
* [Can’t crack that programming problem? Go to sleep](https://m.signalvnoise.com/cant-crack-that-programming-problem-go-to-sleep-or-take-a-walk-930c767e1119)

---

# Libraries

## Rx
[back to top](#readme)
* Main
    * [[Youtube] Introduction to Functional Reactive Programming](https://www.youtube.com/watch?v=_XKX6UQfNGY)
    * [Unit Testing with RxJava](http://alexismas.com/blog/2015/05/20/unit-testing-rxjava/)
    * [RxJava2: Dispose an Observable chain](https://android.jlelse.eu/rxjava2-dispose-an-observable-chain-684e6ca2790)
    * [Concurrency in RxJava 2](https://code.tutsplus.com/tutorials/concurrency-in-rxjava-2--cms-29288)
    * [RxJava - Schedulers - What, when and how to use it?](https://android.jlelse.eu/rxjava-schedulers-what-when-and-how-to-use-it-6cfc27293add)
    * [Learning Observable By Building Observable](https://medium.com/@benlesh/learning-observable-by-building-observable-d5da57405d87)
    * [Rx if the operators could speak](https://medium.freecodecamp.org/rx-if-the-operators-could-speak-58567c4618f1)
    * [Writing Custom Rx Operators Easily with Kotlin](https://upcurve.engineering/custom-rx-operators-kotlin/)
    * [RxJava as event bus, the right way](https://lorentzos.com/rxjava-as-event-bus-the-right-way-10a36bdd49ba)
    * [RxJava & State: The Basics](https://tech.instacart.com/rxjava-state-the-basics-f842eaee7ee1)
    * [Understanding RxJava Subject — Publish, Replay, Behavior and Async Subject](https://blog.mindorks.com/understanding-rxjava-subject-publish-replay-behavior-and-async-subject-224d663d452f?gi=837dc5402ae4)
    * [Understanding RxJava subscribeOn and observeOn](https://proandroiddev.com/understanding-rxjava-subscribeon-and-observeon-744b0c6a41ea)
    * [How we migrated from RxJava1 to RxJava2](https://medium.com/lifesum-healthy-living-simplified/how-we-migrated-from-rxjava1-to-rxjava2-bcf0c9eb1a6f)
    * [When you dont need map](https://blog.danlew.net/2018/02/20/when-you-dont-need-a-map)
    * [[Youtube] Common RxJava Mistakes](https://www.youtube.com/watch?v=QdmkXL7XikQ)
* Error
    * [Error handling in RxJava](http://blog.danlew.net/2015/12/08/error-handling-in-rxjava/)
    * [The RxJava2 Default Error Handler](https://medium.com/@bherbst/the-rxjava2-default-error-handler-e50e0cab6f9f)
    * [Error handling in RxJava/RxKotlin](https://android.jlelse.eu/error-handling-in-rxjava-rxkotlin-e960300990e0)
    * [Rxify: error handling with subjects, relays](https://articles.caster.io/android/rxify-error-handling-with-subjects-relays/)
* Backpressure
    * [Rx java backpressure](https://stackoverflow.com/documentation/rx-java/2341/backpressure/10629/creating-backpressured-data-sources#t=201607290718331225652)
    * [RxJava Backpressure and why should you care?](https://proandroiddev.com/rxjava-backpressure-and-why-you-should-care-369c5242c9e6)
* Android
    * [[Youtube] Exploring RxJava 2 for Android](https://www.youtube.com/watch?v=htIXKI5gOQU)
    * [RxJava cheat sheet, with a pinch of Android](https://zeroturnaround.com/rebellabs/rxjava-cheat-sheet-with-a-pinch-of-android/)
    * [Retrofit 2 and Rx Java call adapter error handling](http://bytes.babbel.com/en/articles/2016-03-16-retrofit2-rxjava-error-handling.html)
    * [Combination of RxJava and DiffUtil](https://hellsoft.se/a-nice-combination-of-rxjava-and-diffutil-fe3807186012)
    * [Server polling and retrying failed operations, with Retrofit and RxJava](https://medium.com/@v.danylo/server-polling-and-retrying-failed-operations-with-retrofit-and-rxjava-8bcc7e641a5a)
    * [Overriding RxAndroid Schedulers in RxJava 2](https://medium.com/@peter.tackage/overriding-rxandroid-schedulers-in-rxjava-2-5561b3d14212)
    * [LCE: Modeling Data Loading in RxJava](https://tech.instacart.com/lce-modeling-data-loading-in-rxjava-b798ac98d80)
    * [MVVM + RxJava: Common Mistakes](http://upday.github.io/blog/mvvm_rx_common_mistakes/)
    * [RxJava2 and Retrofit2 Error Handling on a single place](https://medium.com/mindorks/rxjava2-and-retrofit2-error-handling-on-a-single-place-8daf720d42d6)
    * [Building an AutoCompleting EditText using RxJava](https://proandroiddev.com/building-an-autocompleting-edittext-using-rxjava-f69c5c3f5a40)
    * [[Youtube] Advanced RxJava and Conductor](https://www.youtube.com/watch?v=0XSf7sX2rCQ)
    * [RxJava on the Sign In Screen](https://medium.com/@etiennelawlor/rxjava-on-the-sign-in-screen-9ecb66b88572)
    * [How to make complex requests simple with RxJava in Kotlin](https://blog.mindorks.com/how-to-make-complex-requests-simple-with-rxjava-in-kotlin-ccec004c5d10)
    * [No Cause for Concern — RxJava and Retrofit Throwing a Tantrum](https://medium.com/square-corner-blog/no-cause-for-concern-rxjava-and-retrofit-throwing-a-tantrum-96c9e4ba8a6c)

---

## Dagger
[back to top](#readme)
* [Tasting Dagger 2 on Android](https://fernandocejas.com/2015/04/11/tasting-dagger-2-on-android/)
* [Dependency injection with Dagger 2 - Custom scopes](http://frogermcs.github.io/dependency-injection-with-dagger-2-custom-scopes/)
* [[Yotube] DAGGER 2 - A New Type of dependency injection](https://www.youtube.com/watch?v=oK_XtfXPkqw)
* [[Yotube] The Future of Dependency Injection with Dagger 2](https://www.youtube.com/watch?v=plK0zyRLIP8)
* [A Dagger to Remember](http://arturdryomov.online/posts/a-dagger-to-remember/)
