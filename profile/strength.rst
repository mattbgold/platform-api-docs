Strength
========

Get a user's profile strength. Profile strength is increased as the user connects new provider accounts. 

Get profile strength
-----------------

::

    GET /v2/Profile/{user-id}/Strength

**Response**

.. code:: json

    {
        "ProfileStrength": 85
    }


``ProfileStrength`` will be an integer between 0 and 100.