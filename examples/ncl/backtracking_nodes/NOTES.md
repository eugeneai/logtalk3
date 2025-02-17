________________________________________________________________________

This file is part of Logtalk <https://logtalk.org/>  
Copyright 1998-2022 Paulo Moura <pmoura@logtalk.org>  
SPDX-License-Identifier: Apache-2.0

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
________________________________________________________________________


To load this example and for sample queries, please see the `SCRIPT.txt`
file.

This folder contains a Logtalk version of a spreading activation nodes
backtracking example described in the Net-Clause Language (NCL) manual,
available at:

https://www.cs.cmu.edu/afs/cs/project/ai-repository/ai/lang/prolog/impl/parallel/ncl/0.html

The Logtalk version uses parametric objects to represent the concept of
"net-variables" described in the paper as "global logical variables" and
events to implement the functionality of spreading activation nodes.
When multiple spreading activation nodes fire, all their procedures must
be true by default (in the NCL manual, this corresponds to `netmode(3)`).
