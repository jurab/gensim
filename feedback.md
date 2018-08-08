# Django [serious]

    
# Django [low-priority]
1. Consider prefix of the app in urls. Such as:
```
# Ingredient router
prefix = 'ingredients/'
router.register(prefix + 'ingredient', IngredientViewSet, base_name='ingredients')
router.register(prefix + 'tag', TagViewSet, base_name='tags')
router.register(prefix + 'search', SearchIngredientViewSet, base_name='search')
```





# Programming practices
