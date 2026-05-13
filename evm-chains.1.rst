..
   SPDX-License-Identifier: AGPL-3.0-or-later

   ----------------------------------------------------------------------
   Copyright © 2024, 2025, 2026  Pellegrino Prevete

   All rights reserved
   ----------------------------------------------------------------------

   This program is free software: you can redistribute it and/or modify
   it under the terms of the GNU Affero General Public License as
   published by the Free Software Foundation, either version 3 of the
   License, or (at your option) any later version.

   This program is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU Affero General Public License for more details.

   You should have received a copy of the GNU Affero General Public
   License along with this program.
   If not, see <https://www.gnu.org/licenses/>.


==============
evm-chains
==============

--------------------------------------------------------
Ethereum networks data
--------------------------------------------------------
:Version: evm-chains |version|
:Manual section: 1

Description
===========

This manual page is a reference to the data consumed
by applications using the LibEVM library.

Applications can be retrieved from this package in the
following way.

..  code-block:: javascript

  const
    _ethereum_data_module =
      require(
        "ethereum-data";
  _data_split_get =
    _ethereum_data_module._data_split_get;
  _data_unified_get =
    _ethereum_data_module._data_unified_get;

  const
    _data =
      _data_get();
  const
    _chain_data =
      _data_get(
        <chain-id>);

  console.log(
    _data);
  console.log(
    _chain_data);


Bugs
====

https://github.com/themartiancompany/ethereum-data/-/issues

Copyright
=========

Copyright Pellegrino Prevete. AGPL-3.0.

See also
========

* evm-chains-info
* evm-chains-explorers

.. include:: variables.rst
