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


Design pattern:
	Interpreter

Description:
	"Given a language, define a representation for its grammar along
	with an interpreter that uses the representation to interpret
	sentences in the language."

This pattern can be used with both classes and prototypes.

Logtalk support for Definite Clause Grammars (DCGs) allows straightforward
representation of grammars and thus implementation of this pattern. Our
sample code makes use of tabling (to deal with left-recursion in the
original example) and thus can only be run with B-Prolog, SWI-Prolog, XSB,
or YAP backend Prolog compilers.

