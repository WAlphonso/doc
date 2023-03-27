---
title: Configuration du système
---
{{ fr.DGW }} requiert la configuration suivante :  

## Configuration 

### Spécifications matérielles 

<table>
	<tr>
		<th>

Utilisation légère 
(1-10 sessions simultanées) 
		</th>
		<th>
Utilisation modérée 
(15-75 sessions simultanées) 
		</th>
		<th>
Utilisation massive** 
(75+ sessions simultanées) 
		</th>
	</tr>
	<tr>
		<td>
Processeur à 8 cœurs 
8 Go de RAM 
Adaptateur réseau (1 Go) 
		</td>
		<td>
Processeur à 16 cœurs 
16 Go de RAM 
Adaptateur réseau (1 Go) 
		</td>
		<td>
** Nous recommandons de déployer plusieurs instances de {{ fr.DGW }} dans une [Topologie de type équilibrage de charge](/fr/server/overview/topologies/#topologie-de-type-équilibrage-de-charge) . 
		</td>
	</tr>
</table>

{% snippet icon.badgeInfo %} 
Une instance de {{ fr.DGW }} peut gérer jusqu&apos;à 75 sessions simultanées en conservant de bonnes performances. 
{% endsnippet %}
 
### Exigences logicielles 

* Windows 10 
* Windows Server 2012, 2012 R2, 2016, 2019 ou 2022 
* Microsoft .NET Framework 4.8 

### Conditions requises 

* Chaque licence {{ fr.PHUB }} est fournie avec un {{ fr.DGW }} qui prend en charge jusqu&apos;à 5 sessions simultanées. Contactez notre [équipe des ventes](mailto:sales@devolutions.net) pour plus de sessions simultanées. 
