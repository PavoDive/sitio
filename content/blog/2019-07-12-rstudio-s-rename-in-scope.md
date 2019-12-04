---
title: RStudio's rename in scope
author: Giovanni Pavolini
date: '2019-07-12'
slug: rstudio-s-rename-in-scope
categories:
  - Spanish
tags:
  - R
---

Una de las funcionalidades que encuentro más prácticas de RStudio es la función `Code >> Rename in Scope`, salvajemente traducida (¡!) como "renombrar en alcance".

Esta función sirve para aquellos casos es los que se desea cambiar el nombre de una variable que está presente en varias líneas del código por un nombre nuevo (quizá como resultado de reusar el código). Aunque esto se puede lograr con un simple buscar / reemplazar (en algunos casos con regex), existe el riesgo de cambiar el nombre de otras variables (por ejemplo al actualizar `dt` a `ventasMes` terminar cambiando `dt1` a `ventasMes1`).


La funcionalidad es bastante simple de utilizar, sólo mirá el gif a continuación (tomado de [aquí](https://rviews.rstudio.com/2016/11/11/easy-tricks-you-mightve-missed/)).

![Rename in Scope](/post/2019-07-12-rstudio-s-rename-in-scope_files/tip_rename_in_scope.gif)