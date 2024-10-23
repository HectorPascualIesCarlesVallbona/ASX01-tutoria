Per instal·lar **Slack** a Fedora utilitzant Snap, primer necessitaràs instal·lar **Snapd**, ja que no ve instal·lat per defecte en Fedora. Aquí tens els passos per fer-ho:

1. **Instal·lar Snapd**:
   Obre un terminal i executa els següents comandaments per instal·lar Snapd:

   ```bash
   sudo dnf install snapd
   ```

2. **Activa el socket de Snapd**:
   Un cop Snapd estigui instal·lat, cal activar el socket per assegurar-te que Snap pot funcionar correctament:

   ```bash
   sudo systemctl enable --now snapd.socket
   ```

3. **Crea un enllaç simbòlic**:
   Afegeix un enllaç simbòlic entre `/var/lib/snapd/snap` i el sistema perquè Snap funcioni correctament:

   ```bash
   sudo ln -s /var/lib/snapd/snap /snap
   ```

4. **Reinicia o tanca la sessió** (opcional):
   Després d’instal·lar Snapd, és recomanable tancar la sessió o reiniciar per assegurar que tots els canvis s'apliquin correctament.

5. **Instal·lar Slack**:
   Amb Snapd ja configurat, pots instal·lar Slack executant el següent comandament:

   ```bash
   sudo snap install slack --classic
   ```

6. Un cop finalitzada la instal·lació, podràs llançar Slack des del menú d'aplicacions o executant:

   ```bash
   slack
   ```
