# DocumentFinder

Document Fusion prototype finder for Document based on Convention.

With this convention you don't need to touch the ```root```` or create custom Fusion path for your Document.

Usage
-----

The default suffix is ```.Document```. A document node with a type of ```Your.Package:Product``` will be rendered with the Fusion prototype ```Your.Package:Product.Document```. 

    Ttree:
      Fusion:
        DocumentFinder:
          documentPrototype:
            fallback: 'Your.Package:Default.Document'
            suffix: .Document
    
Acknowledgments
---------------

Development sponsored by [ttree ltd - neos solution provider](http://ttree.ch).

We try our best to craft this package with a lots of love, we are open to
sponsoring, support request, ... just contact us.

License
-------

Licensed under MIT, see [LICENSE](LICENSE)
