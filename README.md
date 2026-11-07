# Sutra beta

Releases and tutorials for **Sutra**, one IDE for SwiftUI, Jetpack Compose, Flutter and Compose Multiplatform.

**[Watch the tutorials →](https://anil291987.github.io/sutra-beta/)** Each feature has a short video, recorded in the app, and the steps to try it.
Sutra is in private beta on macOS; builds are published on this repo's Releases page. Sutra's source code is
private; this repo holds what's published from it.

## iOS

Live SwiftUI previews, playgrounds, building to an iPhone with xtool (no Xcode needed), and help with signing and App Store uploads. [All iOS tutorials →](https://anil291987.github.io/sutra-beta/ios.html)

<table>
  <tr>
    <td width="50%" valign="top"><a href="https://anil291987.github.io/sutra-beta/ios.html#swiftui-preview"><img src="media/swiftui-preview.png" alt="SwiftUI live preview"></a><br><b><a href="https://anil291987.github.io/sutra-beta/ios.html#swiftui-preview">SwiftUI live preview</a></b><br><sub>See a view beside its code as you type. Click an element in the preview to select its code, and ask AI to change just that element.</sub></td>
    <td width="50%" valign="top"><a href="https://anil291987.github.io/sutra-beta/ios.html#swift-playground"><img src="media/swift-playground.png" alt="Swift playgrounds"></a><br><b><a href="https://anil291987.github.io/sutra-beta/ios.html#swift-playground">Swift playgrounds</a></b><br><sub>Xcode-compatible .playground files, with each line's value beside it and print() output in a console.</sub></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><a href="https://anil291987.github.io/sutra-beta/ios.html#xtool-devices"><img src="media/xtool-devices.png" alt="Run on iPhone with xtool"></a><br><b><a href="https://anil291987.github.io/sutra-beta/ios.html#xtool-devices">Run on iPhone with xtool</a></b><br><sub>Build, sign and install SwiftPM apps on a connected iPhone with xtool, on macOS, Linux or Windows (WSL). A free Apple ID works.</sub></td>
    <td width="50%" valign="top"><a href="https://anil291987.github.io/sutra-beta/ios.html#signing-doctor"><img src="media/signing-doctor.png" alt="Signing Doctor"></a><br><b><a href="https://anil291987.github.io/sutra-beta/ios.html#signing-doctor">Signing Doctor</a></b><br><sub>When an iPhone run fails to sign, install or launch, Sutra says why in plain words and offers the fix.</sub></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><a href="https://anil291987.github.io/sutra-beta/ios.html#app-store-check"><img src="media/app-store-check.png" alt="App Store readiness"></a><br><b><a href="https://anil291987.github.io/sutra-beta/ios.html#app-store-check">App Store readiness</a></b><br><sub>Find what App Store Connect or App Review would reject before you upload: missing purpose strings, the privacy manifest, export compliance.</sub></td>
    <td width="50%" valign="top"><a href="https://anil291987.github.io/sutra-beta/ios.html#xcode-debugging"><img src="media/xcode-debugging.png" alt="Debug Xcode projects"></a><br><b><a href="https://anil291987.github.io/sutra-beta/ios.html#xcode-debugging">Debug Xcode projects</a></b><br><sub>Breakpoints, stepping, variables and a console for Swift apps in Xcode projects, on the iOS Simulator or as Mac apps.</sub></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><a href="https://anil291987.github.io/sutra-beta/ios.html#xcode-signing"><img src="media/xcode-signing.png" alt="Signing for Xcode projects"></a><br><b><a href="https://anil291987.github.io/sutra-beta/ios.html#xcode-signing">Signing for Xcode projects</a></b><br><sub>Check an Xcode project's signing for iPhone builds and archives: teams, profiles, certificates and entitlements.</sub></td>
  </tr>
</table>

## Android

Compose previews (approximate and on a real device), running on phones and emulators, Kotlin playgrounds, and a stability check for recomposition. [All Android tutorials →](https://anil291987.github.io/sutra-beta/android.html)

<table>
  <tr>
    <td width="50%" valign="top"><a href="https://anil291987.github.io/sutra-beta/android.html#compose-preview"><img src="media/compose-preview.png" alt="Jetpack Compose preview"></a><br><b><a href="https://anil291987.github.io/sutra-beta/android.html#compose-preview">Jetpack Compose preview</a></b><br><sub>Preview @Preview functions and Activities as you type, on phones, tablets, foldables and dual-screen devices, or render them on a real device.</sub></td>
    <td width="50%" valign="top"><a href="https://anil291987.github.io/sutra-beta/android.html#android-run"><img src="media/android-run.png" alt="Run on phones and emulators"></a><br><b><a href="https://anil291987.github.io/sutra-beta/android.html#android-run">Run on phones and emulators</a></b><br><sub>Pick a connected phone or a running emulator and run the app; Devices &amp; Tools starts emulators and checks the SDK.</sub></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><a href="https://anil291987.github.io/sutra-beta/android.html#compose-stability"><img src="media/compose-stability.png" alt="Compose stability check"></a><br><b><a href="https://anil291987.github.io/sutra-beta/android.html#compose-stability">Compose stability check</a></b><br><sub>Find composables that recompose more than they need to, the unstable classes behind them, and how to fix them, from the Compose compiler's own reports.</sub></td>
    <td width="50%" valign="top"><a href="https://anil291987.github.io/sutra-beta/android.html#kotlin-playground"><img src="media/kotlin-playground.png" alt="Kotlin playgrounds"></a><br><b><a href="https://anil291987.github.io/sutra-beta/android.html#kotlin-playground">Kotlin playgrounds</a></b><br><sub>Kotlin scripts with each line's value beside it, run on the JVM as you type.</sub></td>
  </tr>
</table>

## Flutter

Live widget previews, a full debugger with hot reload, and widget rebuild counts in the editor. [All Flutter tutorials →](https://anil291987.github.io/sutra-beta/flutter.html)

<table>
  <tr>
    <td width="50%" valign="top"><a href="https://anil291987.github.io/sutra-beta/flutter.html#flutter-debugging"><img src="media/flutter-debugging.png" alt="Debug Flutter apps"></a><br><b><a href="https://anil291987.github.io/sutra-beta/flutter.html#flutter-debugging">Debug Flutter apps</a></b><br><sub>Breakpoints (conditional, and logpoints), stepping, variables, a console, and hot reload on save.</sub></td>
    <td width="50%" valign="top"><a href="https://anil291987.github.io/sutra-beta/flutter.html#flutter-rebuilds"><img src="media/flutter-rebuilds.png" alt="Widget rebuild counts"></a><br><b><a href="https://anil291987.github.io/sutra-beta/flutter.html#flutter-rebuilds">Widget rebuild counts</a></b><br><sub>See how often each of your widgets rebuilds, beside its line in the editor and in a list of the hottest widgets.</sub></td>
  </tr>
</table>

## Compose Multiplatform

One project for Android, iOS, desktop and web, with previews of shared UI and its resources. [All Compose Multiplatform tutorials →](https://anil291987.github.io/sutra-beta/multiplatform.html)

<table>
  <tr>
    <td width="50%" valign="top"><a href="https://anil291987.github.io/sutra-beta/multiplatform.html#kmp-targets"><img src="media/kmp-targets.png" alt="Targets and shared previews"></a><br><b><a href="https://anil291987.github.io/sutra-beta/multiplatform.html#kmp-targets">Targets and shared previews</a></b><br><sub>Preview shared composables with their composeResources strings and images, and run the Android, iOS, desktop or web target.</sub></td>
  </tr>
</table>

## Across platforms and AI

Keep your app's platforms in step, and hand work to AI agents you can review. [All Across platforms and AI tutorials →](https://anil291987.github.io/sutra-beta/cross-platform.html)

<table>
  <tr>
    <td width="50%" valign="top"><a href="https://anil291987.github.io/sutra-beta/cross-platform.html#compare-screens"><img src="media/compare-screens.png" alt="Compare screens across frameworks"></a><br><b><a href="https://anil291987.github.io/sutra-beta/cross-platform.html#compare-screens">Compare screens across frameworks</a></b><br><sub>Compare a screen with its version on your app's other platform: what's missing, texts that changed, components that became others.</sub></td>
    <td width="50%" valign="top"><a href="https://anil291987.github.io/sutra-beta/cross-platform.html#port-screen"><img src="media/port-screen.png" alt="Port a screen with an agent"></a><br><b><a href="https://anil291987.github.io/sutra-beta/cross-platform.html#port-screen">Port a screen with an agent</a></b><br><sub>An agent ports a screen to another framework in your other project, then Sutra checks the result against the original and has the agent fix what differs.</sub></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><a href="https://anil291987.github.io/sutra-beta/cross-platform.html#agent-manager"><img src="media/agent-manager.png" alt="The Agent Manager"></a><br><b><a href="https://anil291987.github.io/sutra-beta/cross-platform.html#agent-manager">The Agent Manager</a></b><br><sub>Hand tasks to AI agents, run several at once, and review their plans, commands and changes before you keep them.</sub></td>
  </tr>
</table>

<sub>The videos show Sutra with sample projects. Builds, devices and AI replies in them are simulated, so they always look the same; on your Mac they're real.</sub>
