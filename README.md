# 📱 Deveinvertir CDF.[14/06, 14:54] mulumbardev: <!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Code Firebase AppCheck à copier</title>
</head>
<body>
  <h2>Code Firebase AppCheck & Retrofit – À copier pour ton dépôt</h2>
  <textarea id="code" rows="30" style="width:100%;font-size:14px;">
// === ApiWithAppCheckExample.java ===

public class ApiWithAppCheckExample {

    private interface YourExampleBackendService {
        @GET("yourExampleEndpoint")
        Call<List<String>> exampleData(
            @Header("X-Firebase-AppCheck")()
        .create(YourExampleBackendService.class);

    public void callApiExample() {
        FirebaseAppCheck.getInstance()
            .getAppCheckToken(false)
            .addOnSuccessListener(new OnSuccessListener<AppCheckToken>() {
                @Override
                public void onSuccess(@NonNull AppCheckToken appCheck();
            // ... (utilise ce token pour un appel API sensible)
        }
    });

// === (Kotlin ou pseudo-JS rapide) ===

Firebase.appCheck.limitedUseAppCheckToken.addOnSuccessListener {
    // ...
}
  </textarea>
  <br>
  <button onclick="navigator.clipboard.writeText(document.getElementById('code').value)">Copier tout le code</button>
</body>
</html>
[14/06, 14:56] mulumbardev: // === ApiWithAppCheckExample.java ===

public class ApiWithAppCheckExample {

    private interface YourExampleBackendService {
        @GET("yourExampleEndpoint")
        Call<List<String>> exampleData(
            @Header("X.class);

    public void callApiExample() {
        FirebaseAppCheck.getInstance()
            .getAppCheckToken(false)
            .addOnSuccessListener(new OnSuccessListener<AppCheckToken>() {
                @Override
                public void onSuccess(@NonNull AppCheckToken appCheckToken) {
                    String token = appCheckToken.getToken();
                    Call<List<String>> apiCall =
                        yourExampleBackendService.exampleData(token);
                    // ... (exécution de l'appel, gestion de la réponse)
                }
            });
    }
}

// === Exemple Limited Use App Check Token ===

FirebaseAppCheck.getInstance()
    .getLimitedUseApp appCheckToken.getToken();
            // ... (utilise ce token pour un appel API sensible)
        }
    });

// === (Kotlin ou pseudo-JS rapide) ===

Firebase.appCheck.limitedUseAppCheckToken.addOnSuccessListener {
    // ...
}
