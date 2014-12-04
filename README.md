select2-sortable
================

Plugin that makes [select2](https://github.com/ivaynberg/select2) multiple select sortable out of the box.

Usage:

	// init select2 sortable
	$(select2multiselect).select2Sortable();
	
	// destroy select2 sortable
	$(select2multiselect).select2Sortable('destroy');
	
	// manually trigger the sorting
	$(select2multiselect).select2SortableOrder();
	
	// custom options
	$(select2multiselect).select2Sortable({
		bindOrder: 'formSubmit' // or `sortableStop`,
		sortableOptions: {
			// please refer to jQuery UI sortable API (http://api.jqueryui.com/sortable/)
		}
	});

