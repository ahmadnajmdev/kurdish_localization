
### Getting Started


```
import 'package:flutter_sorani_localization/flutter_kurdish_localization.dart';
import 'package:flutter_sorani_localization/kurdish_cupertino_localization_delegate.dart';
import 'package:flutter_sorani_localization/kurdish_material_localization_delegate.dart';
import 'package:flutter_sorani_localization/kurdish_widget_localization_delegate.dart';
```

Add these two delegates to *localizationsDelegates* array


**KurdishMaterialLocalizations.delegate** For text and dates localization
**KurdishWidgetLocalizations.delegate**  For text and UI directionality

```dart
return MaterialApp(
	localizationsDelegates: [
		..
		KurdishMaterialLocalizations.delegate,
		KurdishWidgetLocalizations.delegate,
		...
	],
	supportedLocales: [ Locale('ckb') ]
	ocale: Locale('ckb')
 )
```

-----
### Translations are available now!




