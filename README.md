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
<!-- index.html - Site Deveinvertir (multi-pages) --><!DOCTYPE html><html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Deveinvertir</title>
  <style>
    body {
      font-family: sans-serif;
      background: #f5f7fa;
      margin: 0;
    }
    header {
      background: #2c3e50;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      background: #34495e;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    nav a {
      color: white;
      text-decoration: none;
      padding: 1rem;
      display: inline-block;
    }
    nav a:hover {
      background: #2c3e50;
    }
    main {
      padding: 2rem;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bienvenue sur Deveinvertir</h1>
  </header>  <nav>
    <a href="#accueil">Accueil</a>
    <a href="#caisse">Caisse d'investissement</a>
    <a href="#deja">Déjà investi</a>
    <a href="#temoignages">Témoignages</a>
    <a href="#transactions">Historique</a>
    <a href="#invitation">Lien d'invitation</a>
    <a href="#profil">Profil</a>
    <a href="#agents">Agents</a>
    <a href="#recharge">Recharge</a>
    <a href="#retrait">Retrait</a>
    <a href="#admin">Super Agent / Admin</a>
  </nav>  <main>
    <section id="accueil">
      <h2>Page d'accueil</h2>
      <p>Bienvenue sur la plateforme Deveinvertir.</p>
    </section><section id="caisse">
  <h2>Caisse d'investissement</h2>
  <p>Déposer pour investir ici.</p>
</section>

<section id="deja">
  <h2>Déjà investi</h2>
  <p>Voir les projets dans lesquels vous avez déjà investi.</p>
</section>

<section id="temoignages">
  <h2>Témoignages</h2>
  <p>Ce que nos utilisateurs disent de nous.</p>
</section>

<section id="transactions">
  <h2>Historique de transactions</h2>
  <p>Suivez toutes vos opérations financières.</p>
</section>

<section id="invitation">
  <h2>Lien d'invitation</h2>
  <p>Partagez votre lien et gagnez des bonus.</p>
</section>

<section id="profil">
  <h2>Profil</h2>
  <p>Gérez vos informations personnelles.</p>
</section>

<section id="agents">
  <h2>Agents de retrait</h2>
  <p>Liste des agents disponibles pour retrait.</p>
</section>

<section id="recharge">
  <h2>Agents de recharge</h2>
  <p>Rechargez votre compte via nos agents.</p>
</section>

<section id="retrait">
  <h2>Super Agents</h2>
  <p>Responsables régionaux et superviseurs.</p>
</section>

<section id="admin">
  <h2>Admin</h2>
  <p>Panneau de contrôle administrateur.</p>
</section>

  </main>
</body>
</html>